# Terminus releases

Builds of Terminus, a macOS app for working with several coding agents in one window with a
shared memory. The source code is private; this repository only hosts the release files.

Installed copies of Terminus check here for updates. Each release has:

- `Terminus_<version>_aarch64.app.tar.gz`: the app, used by the built-in updater.
- `Terminus_<version>_aarch64.dmg`: the disk image for a fresh install.
- `latest.json`: the version, the archive's SHA-256 and an Ed25519 signature. Terminus checks
  the signature against a key built into the app before installing anything.

More at https://akshng.github.io/terminus-site/
