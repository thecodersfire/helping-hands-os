# Built-in features for helping-hands-os

Purpose: volunteer coordination

1. **organize project files** — run helping-hands-os-workspace. It creates ~/Documents/helping-hands-os-workspace/ with Inbox, Projects, Archive folders.
2. **draft a session plan** — run helping-hands-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/helping-hands-os-session-plans/.
3. **check task readiness** — run helping-hands-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/helping-hands-os-workspace features/helping-hands-os-plan features/helping-hands-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for volunteer coordination:

1. **Audacity** — org.audacityteam.Audacity
2. **Foliate** — com.github.johnfactotum.Foliate
3. **KeePassXC** — org.keepassxc.KeePassXC

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
