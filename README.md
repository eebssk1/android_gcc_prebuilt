# android_gcc_prebuilt
Prebuilt modern GCC to build c,c++ program for android.(Release only)

Notes

For the toolchain to work correctly do not forget to append "-sysroot", since the sysroot location at building time is not in a standard location that you can normally install the toolchain into.

The toolchain is built with the newest dependencies at that time,if your system doesn't have the required dependency versions, I provided them in "deps" directory, you can install them to "/usr/local" or use "LD_LIBRARY_PATH".

If your encountered compilation errors on some applications, this might because the sysroot is from LLVM's, which is not very compatible with GCC. I have already done something to avoid them, but it's still not very good. If you find any solutions to this, please open an issue and tell the way.

You can download then on the release section > [ClickMe](https://github.com/eebssk1/android_gcc_prebuilt/releases)

**For the sources please see my other repos**
