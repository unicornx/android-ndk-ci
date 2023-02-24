This repo is just used to simulate android NDK befoer google releases offiical
version that supports riscv64.

Based on android ndk packages from https://ci.android.com/builds/branches/aosp-master-ndk/grid (linux),
but stripping some other items except the sysroot, due to space limitation from github.

Before usage, make sure to remove the existing toolchains/llvm/prebuilt/linux-x86_64/sysroot/usr/lib/riscv64-linux-android,
which is a symbol link and re-create anther one with the same name and point to the usr/lib/riscv64-linux-android/
of repo https://android.googlesource.com/toolchain/prebuilts/sysroot/platform/riscv64-linux-android.

