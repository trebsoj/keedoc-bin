# KeeDoc — binary releases

This repository hosts only the compiled Linux release bundles for
[KeeDoc](https://keedoc.app), a secure, encrypted vault for
your documents. It exists so that the AUR package `keedoc-bin` and other
distribution channels can fetch binaries anonymously.

The application source code is closed and lives in a private repository.
KeeDoc is proprietary software, distributed under its own EULA (included as
`share/doc/keedoc/EULA.md` inside each release bundle); only the packaging
metadata attached to each release (`PKGBUILD`, `LICENSE`) is open (0BSD).

## Releases

Each release contains:

- `keedoc-linux-x86_64.tar.gz` — the Linux release bundle
- `keedoc-linux-x86_64.tar.gz.sha256` — its checksum
- `PKGBUILD` — ready-to-use AUR recipe for `keedoc-bin`
- `LICENSE` — 0BSD license covering the `PKGBUILD` recipe
