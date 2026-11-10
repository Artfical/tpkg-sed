# sed

GNU sed 4.9

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install sed
```

| | |
|---|---|
| Version | 4.9 |
| Licence | GPL-3.0-or-later |
| Upstream | - |
| Needs | none |
| Needs tOS build | 619 or newer |
| Size | 69256 bytes (117320 unpacked) |
| SHA-256 of the `.tpkg` | `10352c74c00e9944880e53d15c30c79d374b4524549b83770e30504997ea1af5` |

## Commands it adds

| Command | Runs |
|---|---|
| `sed` | `bin/sed` |

## Download

The package file (`sed-4.9.tpkg`) and the sources it was built from are the assets of the
[v4.9 release](https://github.com/Artfical/tpkg-sed/releases/tag/v4.9).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `sed-4.9.tar.xz`

Check a download: `sha256sum sed-4.9.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0-or-later. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
