# M1 Laser Range Hold v0.1.10

GHPC M1/M1IP laser-range mod. Invalid smoke, dust or missing returns blink `0000`, while retaining the last valid ballistic range.

## Install or update

1. Exit GHPC normally.
2. Download `M1-Laser-Range-Hold-v0.1.10.zip` from the latest GitHub release (not the automatic source archives).
3. Extract it into the folder containing `GHPC.exe`. The archive includes the `Mods` directory, so the result is `Mods/M1LaserRangeHold.dll`.
4. Replace the existing file. Keep only one copy of this plugin in `Mods`; do not install old and new DLLs together.

MelonLoader is required. Reference environment: MelonLoader 0.7.3 and GHPC 20261014. No companion vehicle MOD is required.

## What changed in v0.1.10

This release republishes the current known-good 0.1.9 implementation with synchronized release, archive and DLL version metadata. It also restores the correct `Mods` archive layout and clarifies installation. Gameplay method bodies are unchanged; no new ranging behavior is claimed.

Earlier downloads under the `v0.1.2` release (including the archive named `v0.1.2.1`) contained DLL version 0.1.9. Updating to v0.1.10 resolves that version-label mismatch.

Known limitations: failed ranging does not re-engage lead tracking; particle-dust detection is approximate. Only native M1/M1IP identities and conversions retaining those identities are in scope.

SHA-256 checksums are included in `SHA256SUMS.txt`. This package contains no game assemblies, private logs, user configuration or backups.
