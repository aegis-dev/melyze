# melyze

## Building with cmake

```
mkdir build
cd build
cmake -DCMAKE_BUILD_TYPE=Release -DCMAKE_TOOLCHAIN_FILE=${ANDROID_NDK_HOME}/build/cmake/android.toolchain.cmake -DANDROID_ABI=armeabi-v7a -DANDROID_NATIVE_API_LEVEL=19 ..
cmake --build .
```