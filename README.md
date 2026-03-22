# GitHub Update Repo Template

This folder is a ready-to-copy template for the public repository that only serves update metadata and release notes.

## Recommended structure

```text
manifest.json
current/
  zh-Hans.md
  en.md
releases/
  1.2.1/
    zh-Hans.md
    en.md
```

## Maintenance flow

1. Upload this structure to a public GitHub repository.
2. Replace `YOUR_NAME/YOUR_UPDATE_REPO` in `manifest.json`.
3. Replace `downloadURL` and `detailsURL` with your real website links.
4. Edit the Markdown files directly for release notes.
5. For each new release:
   - create a new `releases/x.y.z/` directory
   - update `manifest.json` with the new `version`, `build`, and release-note URLs
   - update `current/` if you also want the About page to show the new current-version overview
