Copy of the AOSP voice interaction test project from 6.0.1 r3. Packaged project as a Gradle project and removed lines that require testing access.

## Build
Typical gradle project

```
./gradlew assembleDebug
```

## Installation
I was unable to test this on my N7 due to being unable to install system apps even with root. Theoretically you should be able to root your device, install the generated apk as a system app, and finally somehow you select this project as the detector.

## Source
The original source can be found in AOSP.

https://android.googlesource.com/platform/frameworks/base/+/android-6.0.1_r3/tests/VoiceInteraction/

