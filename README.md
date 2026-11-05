# Pixel 7 iOS port (panther, Tensor G2), saved 2026-11-04

- pixelios-kernel/: the port, branch wip/panther-bringup, commit 7430aeb plus later uncommitted touch work in the working tree.
  Start with device/google/panther/docs/BRINGUP.md.
- pixelios-userland/: the iOS image recipe.
- session-files/: boot images (ios2.img = iOS with touch driver), test logs, helper scripts, the live device tree.
- pixelios-kernel-commits.bundle: the git history as one file.
- memory/: Claude's project notes.

Kept in place (not copied here):
- ~/pixelios-artifacts: kernel build, iOS image (panther/ios-root.img), iPhone X firmware, tools, Google sources.
- ~/pixelios-backups/panther-20261104T004337Z: phone partition backup, holds IMEI and calibration data. Keep private.
- ~/.local/opt: Arm toolchain and the Python environment.

Do not commit or upload Apple firmware, session-files/panther-live, or the partition backup. The dtb in panther-live holds the phone's serial.
