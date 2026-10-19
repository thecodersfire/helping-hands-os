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

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for volunteer coordination:

1. **Zotero** — manage research sources and citations (org.zotero.Zotero)
2. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
3. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
4. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
5. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
6. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
7. **Anki** — create spaced-repetition study decks (net.ankiweb.Anki)
8. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
9. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
10. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
