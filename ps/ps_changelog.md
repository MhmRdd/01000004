## 4.0.2b-epilogue

- Migrated to LibXposed API 101 for modern framework support.
- Upgraded compileSdk to 36 and AGP to 8.9.3.
- Rewrote hook system from annotation-based to interceptor chain pattern.
- Replaced module lifecycle from onPackageLoaded to onPackageReady.
- Fixed update installer crashing on content:// URIs from DownloadManager.
- Added FileProvider for reliable APK installation.
- Removed duplicate update logic and dead code (6 files removed).
- Fixed race condition in forced update download flow.
- Secured changelog fetch with certificate pinning.
- Fixed attestation config editor reverting user input while typing.
- Removed polling loop that overwrote attestation config fields during editing.
- Added inline validation warnings for attestation config fields.
- Removed error icon from Corrupt DroidGuard Response Token switch.

## 4.0.1b

- Fix various bugs on startup.
- Remove TLS/SSL requirement for local/private networks for RKA.
- Unlock packages attestations for global use.
- Enhance performance of connectivity.
- Enforce guards of RKA.
- Removed AntiTracking to prevent rampant abuse.
- Resolved an issue of sync when updating PlayStrong.