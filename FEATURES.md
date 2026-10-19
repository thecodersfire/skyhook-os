# Built-in features for skyhook-os

Purpose: cloud platform work

1. **prepare a technical project** — run skyhook-os-workspace. It creates ~/Documents/skyhook-os-workspace/ with Design, Builds, Logs folders.
2. **plan a build or maintenance session** — run skyhook-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/skyhook-os-session-plans/.
3. **check technical change readiness** — run skyhook-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/skyhook-os-workspace features/skyhook-os-plan features/skyhook-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for cloud platform work:

1. **DB Browser for SQLite** — org.sqlitebrowser.sqlitebrowser
2. **Wireshark** — org.wireshark.Wireshark
3. **KeePassXC** — org.keepassxc.KeePassXC

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
