### v0.0.5 (47)

- Commit: `3bdf3df`
- ABI(s): arm64-v8a, armeabi-v7a, x86, x86_64

- Added fallback when `setns` fails with `pidfd_open` in some kernel version alike 4.19
- Introduced Mount Rule System, more details in README.md
- Updated README.md & added acknowledgment to ZygiskAssistant for the main idea.
- Fixed an issue where module.prop could go missing due to excessive & synchronous writing on prop from differences processes
- Added support for `umount_persist`/`umount_persists` to evaluate Mount Rule System once only (to avoid `whitelist` excessive evaluation & causing overheating issues).
- Create initial setup for `/data/adb/nohello` with default `umount` & `umount_persist`.