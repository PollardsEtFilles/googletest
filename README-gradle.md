
# Google Test #

Build x86 and x64 shared library for c++0x
  * `./gradlew clean build`

Install libgoogletest.dylib to ${HOME}/lib/googletest with includes to ${HOME}/lib/googletest/include

  * `./gradlew install32BitSharedLibToHomeLib`
    * Installs to `lib/googletest/x86/libgoogletest.dylib`
  * `./gradlew install64BitSharedLibToHomeLib`
    * Installs to `lib/googletest/x64/libgoogletest.dylib`

