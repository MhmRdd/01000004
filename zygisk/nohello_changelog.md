### v0.0.7 (53)

- Commit: `4d53ecf`
- ABI(s): arm64-v8a, armeabi-v7a, x86, x86_64

- Updated README.md
- Updated compatibility & requirements in post-fs-data.sh
- Switched to Mount Rule System for better compatibility and liability.
- Unmounting logic is moved to preAppSpecialize instead of hooking ar_unshare.
- Added a temporary workaround for zygisk based detections introduced in apps like SBI Cards, Santander, ... (was fixed in ZN 1.2.9)
- Re-worked a fix for zygisk detection (ptrace message leaking bug in Kernels 6.0 and below)
- Now the module will skip unmounting stage if there are conflicting modules.
- Added comment supports in umount file by adding # at the beginning of a line.

Signed-off-by: Mohammed Riad <52679407+MhmRdd@users.noreply.github.com>