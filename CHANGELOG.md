# Changelog

## 2026-10-17

- Add this `CHANGELOG.md`.
- Fix the `README.md` install step that named `lvrbot.reply`; the script reads `lvrbot.replies`, a JSON list copied from `lvrbot.replies-sample`.
- Add a `README.md` install step to create an empty `lvrbot.posts`. The script opens it for reading before ever writing to it, so a fresh install failed with `FileNotFoundError` on every run.
- Update the copyright notices in `LICENSE` and `README.md` to `Copyright (c) 2024-2026 Greg Chetcuti <greg@chetcuti.com>`.
