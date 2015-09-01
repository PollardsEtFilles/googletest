
# Google Test #

Build x86 and x64 shared library for c++0x
  * `./gradlew clean build`

Install libgoogletest.dylib to ${HOME}/lib/googletest with includes to ${HOME}/lib/googletest/include

  * `./gradlew install32BitSharedLibToHomeLib`
  * `./gradlew install64BitSharedLibToHomeLib`

Both the shared library installs write to the same file: libgoogletest.dylib
