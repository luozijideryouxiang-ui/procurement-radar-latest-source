# ProcurementRadar Latest Source Snapshot

Latest source snapshot for the ProcurementRadar SwiftUI macOS/iOS app.

Snapshot source:
- Local repository: `/Users/momo/Documents/Codex/2026-06-19/procurement-radar-apple-swiftui-macos-human`
- Local commit: `b2ae5d9 Add iOS simulator validation script`
- Archive file: `procurement-radar-latest-source.zip`
- Archive SHA-256: `10250124487f97a794fd8493f6c0dea96c5fde94e73d355db88aec404676bac9`

GitHub web upload has a 25MB per-file limit, so the archive is stored as split parts:
- `procurement-radar-latest-source.zip.part-aa` SHA-256: `19440714c98e26a9baac88f11af6306aa25007d799828e5867234fd1aed5e36c`
- `procurement-radar-latest-source.zip.part-ab` SHA-256: `2fafcca60f65627b0de63ffb61617329dcad5fe7ba787da7d7ce90df8ff9e23b`
- `procurement-radar-latest-source.zip.part-ac` SHA-256: `4b374f8c757c02788ef22ead33c83a5646729e43075682354e7f0424ace98e07`

To restore the archive on macOS/Linux:

```sh
cat procurement-radar-latest-source.zip.part-* > procurement-radar-latest-source.zip
shasum -a 256 procurement-radar-latest-source.zip
```

The restored archive hash should be:

```text
10250124487f97a794fd8493f6c0dea96c5fde94e73d355db88aec404676bac9
```

Notes:
- The archive was generated from `git archive HEAD`.
- It contains the latest tracked source and assets at the commit above.
- It excludes `.git`, build caches, and untracked runtime logs.
- This repository is used for latest-version backup and version management.
