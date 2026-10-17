# Changelog

## 2026-10-17 (retirement)

- Add an archive notice to the top of `README.md`: lvrbot is retired because Reddit is ending public API access, which the bot needs to read and reply to posts. Links to TechCrunch's coverage of the shutdown.
- Remove the `https://lvrbot.com` link from `README.md`, since the domain is being left to expire, and drop "The code is left here for reference." from the archive notice.
- Add `ACR.md` with an AI Code Rating of B0a (all code written by hand; AI helped with docs only), and its badge under the `README.md` title.

## 2026-10-17

- Add this `CHANGELOG.md`.
- Fix the `README.md` install step that named `lvrbot.reply`; the script reads `lvrbot.replies`, a JSON list copied from `lvrbot.replies-sample`.
- Add a `README.md` install step to create an empty `lvrbot.posts`. The script opens it for reading before ever writing to it, so a fresh install failed with `FileNotFoundError` on every run.
- Update the copyright notices in `LICENSE` and `README.md` to `Copyright (c) 2024-2026 Greg Chetcuti <greg@chetcuti.com>`.
