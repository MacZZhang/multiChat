# multiChat 1.4.6

Starting with this release, multiChat uses Sparkle 2 updates distributed from the NAS instead of relying on GitHub metadata or browser downloads.

- Release notes, archives, and the appcast are now served from `maczhang.nat100.top`.
- Updates can be downloaded, verified with Ed25519, installed, and relaunched in the app.
- Fixed the release-overview sheet blocking automatic termination during installation.
- Improved source-app detection after WeChat updates, startup scan retries, and plan restoration.
- Hardened validation for custom icons, Bundle ID mappings, and synchronized records.

After installing 1.4.6, future releases will update directly in the app through Sparkle.
