# mpv-android-build

Automated build and release workflow for `mpv-android` native libraries (`libmpv.so`).

Tracks the upstream [mpv-android/mpv-android](https://github.com/mpv-android/mpv-android) repository and builds portable precompiled `libmpv.so` libraries for Android applications.

## Architectures Supported

- `arm64-v8a`
- `armeabi-v7a`
- `x86`
- `x86_64`

## Release Assets

Each release provides:
- `mpv-android-libs.tar.gz`: Precompiled `libmpv.so` for all architectures organized by ABI folder (`arm64-v8a/libmpv.so`, etc.).
- `mpv-android-libs.zip`: Zip alternative for convenient extraction.
