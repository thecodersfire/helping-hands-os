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

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
2. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
3. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
4. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
5. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
6. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
7. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
8. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
9. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
10. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
11. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
12. **LMMS** (io.lmms.LMMS) — compose electronic music and loops.
13. **GNOME Weather** (org.gnome.Weather) — check local weather conditions.
14. **GNOME Boxes** (org.gnome.Boxes) — test workflows in virtual machines.
15. **Disk Usage Analyzer** (org.gnome.baobab) — find large files and manage storage.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **Kontact** (org.kde.kontact) — organize email, calendars, contacts, and schedules in one workspace.
2. **KMyMoney** (org.kde.kmymoney) — track household or small-business accounts, categories, and budgets.
3. **Marknote** (org.kde.marknote) — keep structured Markdown notes and project notebooks.
4. **KleverNotes** (org.kde.klevernotes) — capture and manage Markdown notes for projects and research.
5. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
6. **Kate** (org.kde.kate) — edit configuration, code, notes, and structured project files.
7. **Ark** (org.kde.ark) — open and create common project archive files.
8. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
9. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
10. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
11. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.
12. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
13. **KAlarm** (org.kde.kalarm) — schedule reminders and recurring task alerts.
14. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.
15. **Konsole** (org.kde.konsole) — run shell commands and inspect development or system tasks.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.

## Blender included in every setup

Blender (org.blender.Blender) is included in every setup for 3D modeling, animation, rendering, and video editing. Installers fetch it from Flathub; Blender’s own license and terms apply.

## Fifteen additional purpose-specific applications

The setup adds these Flathub applications for volunteer coordination. Applications are fetched from Flathub by the setup script; each app keeps its own licensing and terms.

1. **PDF Arranger** (com.github.jeromerobert.pdfarranger) — Reorder, rotate, split, and merge PDF pages.
2. **LocalSend** (org.localsend.localsend_app) — Transfer files directly between nearby devices on your local network.
3. **Joplin** (net.cozic.joplin_desktop) — Organize notes and checklists in notebooks.
4. **KBackup** (org.kde.kbackup) — Create user-selected backup archives of files and folders.
5. **Déjà Dup** (org.gnome.DejaDup) — Create user-configured file backups to a chosen destination.
6. **KRename** (org.kde.krename) — Batch rename photo, document, and project files.
7. **Tellico** (org.kde.tellico) — Catalog books, media, games, and other collections.
8. **Skanpage** (org.kde.skanpage) — Scan and arrange multipage documents from a connected scanner.
9. **Merkuro** (org.kde.merkuro) — Organize calendars, contacts, and tasks.
10. **KClock** (org.kde.kclock) — Use alarms, timers, and a stopwatch.
11. **QGIS** (org.qgis.qgis) — Create and analyze geographic information system projects.
12. **Marble** (org.kde.marble) — Explore maps and a virtual globe for route and place context.
13. **KGeography** (org.kde.kgeography) — Practice place and map recognition.
14. **KGeoTag** (org.kde.kgeotag) — Review and edit photo location metadata.
15. **Kst** (org.kde.kst) — Display and inspect scientific measurement and time-series data.
