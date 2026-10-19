# Built-in features for cutscene-os

Purpose: video editing

1. **prepare a creative project** — run cutscene-os-workspace. It creates ~/Documents/cutscene-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run cutscene-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/cutscene-os-session-plans/.
3. **check project and export readiness** — run cutscene-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/cutscene-os-workspace features/cutscene-os-plan features/cutscene-os-check "$HOME/.local/bin/"
