# Winlator Proton

Wine Proton builds for Winlator Tuning Steam shortcuts. The app downloads
these files from this release. It does not follow GameNative or any other
upstream repository.

Each file is an unmodified copy of the named upstream release. Proton and
Wine are their own licenses.

## Catalog

| Proton | Arch | Run with | Origin | File | SHA-256 |
|---|---|---|---|---|---|
| 9 | arm64ec | WoW64 | Tuning | `proton-9.0-arm64ec.tar.zst` | `5f9375640479a5b2c4c3998fda689bb5085febc8fcdb7b6998c79d925392991a` |
| 9 | x86_64 | Box64 | Tuning | `proton-9.0-x86_64.tar.zst` | `b4688130cd15818c2c46e66f2f7f7146d459a2d95bee1b3daf970f50dc4f8331` |
| 10.0-5 | arm64ec | WoW64 | Tuning | `proton-wine-10.0-5-arm64ec.tar.zst` | `8cf0db4bb5e7e266e9e22e45e76722fb62cfbbf4e5e0e167a90c05c508e310ee` |
| 10.0-5 | x86_64 | Box64 | Tuning | `proton-10.0-5-x86_64.wcp` | `2a5759e48b5f856d36eedac3e5159054629260a792fcf9c167140e02c06d8f0c` |
| 11.0-1 | arm64ec | WoW64 | Tuning | `proton-wine-11.0-1-arm64ec.wcp.xz` | `a360f849f0ce3a808dacec854f25a641735a62ecc0eca8e09b7b7f7ff44041ff` |
| 11.0-2 | arm64ec | WoW64 | GameNative | `proton-wine-11.0-2-arm64ec.wcp.xz` | `56ecc2ea71078847a5c8a053522c56baff5b455141752bf014a72ae23d3c5d66` |
| 11.0-2 | x86_64 | Box64 | Bannerlator | `proton-11.0-2-x86_64.wcp` | `bd53db23fc47bd88e53b3cf314259ce0cfe14f2525fe7807246660b804654bc2` |
| DroidDeck 11.0-12.3 | arm64ec | WoW64 | Bannerlator | `DroidDeck-proton-11.0-12.3-arm64ec.wcp` | `b88e121021403fdd3133260a9000024c6549732fd7d33436f30a47c97cb169be` |
| DroidDeck 11.0-12.3 | x86_64 | Box64 | Bannerlator | `DroidDeck-proton-11.0-12.3-x86_64.wcp` | `0dd99309919b77a8701fbf5ddaf698ea646c630ebec86b52d4ff359fb8572361` |

11.0-1 is the Proton the Steam container uses today.

## Sources

- Tuning 9, 10.0-5 and 11.0-1: `Other-backup/winlator-imagefs-v2` releases `c` and `d`.
- GameNative 11.0-2 arm64ec: `GameNative/proton-wine` release `proton-11.0-2-20261110`, file built for Winlator CMOD and Ludashi.
- Bannerlator Proton 11.0-2 x86_64 and DroidDeck-Proton 11.0-12.3: `The412Banner/proton-wine` release `build-bionic-layers-20261030-v16`.

## Release

The binaries are release `protons`, not files in git.

```
https://github.com/palazos/winlator-proton/releases/download/protons/<file>
```
