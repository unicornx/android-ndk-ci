This repo is just used for building of Chrome(android riscv64), and
simulate android NDK befoer google releases offiical version that 
supports riscv64.

Based on android ndk packages from
<https://ci.android.com/builds/branches/aosp-master-ndk/grid> (linux),
but stripping some other items (expecially the clangs) and keep some,
such as sysroot etc. due to space limitation from github.

Note, following entries are symbol files, you may have to update
them to correct position:
- toolchains/llvm/prebuilt/linux-x86_64/bin
- toolchains/llvm/prebuilt/linux-x86_64/lib
