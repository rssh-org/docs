# rssh docs

Site and content for [rssh](https://github.com/rssh-org/rssh), served by GitHub Pages at <https://rssh.ofcoder.com>.

- RSSH is available for HarmonyOS phones and PCs through [Huawei AppGallery](https://appgallery.huawei.com/app/detail?id=com.rssh.app&channelId=SHARE&source=appshare). Search for **RSSH** in AppGallery on the device; the store supplies the matching phone or PC package.
- Keep platform availability and installation instructions in `index.html` and the English/Chinese articles consistent with the main repository's READMEs.
- Repo root **is** the site root (Pages source: `main` branch, `/` path).
- Content migrated from `docs/` in the main rssh repo, plus the finished video cuts in `video/*.mp4`.
- The welcome GIFs (`welcome-*.gif`) are re-recorded by `scripts/record-welcome-gifs.mjs` in the main rssh repo; it records into this checkout (`RSSH_DOCS_DIR` overrides the path).
- `video/` tracks only the mp4 cuts; the landing page, image symlinks and narration files stay local-only (gitignored).
