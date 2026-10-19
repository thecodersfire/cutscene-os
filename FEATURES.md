# Built-in features for cutscene-os

Purpose: video editing

1. **prepare a creative project** — run cutscene-os-workspace. It creates ~/Documents/cutscene-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run cutscene-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/cutscene-os-session-plans/.
3. **check project and export readiness** — run cutscene-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/cutscene-os-workspace features/cutscene-os-plan features/cutscene-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for video editing:

1. **GIMP** — org.gimp.GIMP
2. **Inkscape** — org.inkscape.Inkscape
3. **Krita** — org.kde.krita

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for video editing:

1. **OBS Studio** — record or stream sessions (com.obsproject.Studio)
2. **VLC** — review media files (org.videolan.VLC)
3. **Audacity** — edit audio recordings (org.audacityteam.Audacity)
4. **Scribus** — lay out print-ready publications (org.scribus.Scribus)
5. **GNOME Sound Recorder** — capture voice and field notes (org.gnome.SoundRecorder)
6. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
7. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
8. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
9. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
10. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
