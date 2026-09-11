# 2026-09-10: Source Han Sans local customization

Chinese templates use `Source Han Sans SC VF` as the primary font.

- Installed the open-source variable font through Homebrew.
- Removed the TsangerJinKai02 web-font declarations from the nine Chinese templates.
- Updated the Chinese fallback stack and PDF font checks.
- Synced the same changes to the shared agent skill at `~/.agents/skills/kami`.

Upstream updates may overwrite this local customization. Reapply this change after running the Kami updater.
