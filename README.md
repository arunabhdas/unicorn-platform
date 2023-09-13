# unicorn-platform
Unicorn Store is an ecommerce platform built using Flutter


## Steps

* Run flutter channel stable
```
==> flutter channel stable
Downloading package sky_engine...                                  716ms
Downloading flutter_patched_sdk tools...                         1,273ms
Downloading flutter_patched_sdk_product tools...                 1,294ms
Downloading darwin-arm64 tools...                                   9.8s
Downloading darwin-arm64/font-subset tools...                      641ms
Switching to flutter channel 'stable'...
Upgrading engine...
Downloading Darwin arm64 Dart SDK from Flutter engine cdbeda788a293fa29665dc3fa3d6e63bd221cb0d...
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
Building flutter tool...
Resolving dependencies...
Got dependencies.
Downloading package sky_engine...                                  487ms
Downloading flutter_patched_sdk tools...                         1,171ms
Downloading flutter_patched_sdk_product tools...                 1,169ms
Downloading darwin-arm64 tools...                                   9.4s
Downloading darwin-arm64/font-subset tools...                      701ms
Successfully switched to flutter channel 'stable'.
To ensure that you're on the latest build from this channel, run 'flutter upgrade'
```

* Run flutter upgrade

```
==> flutter upgrade
Upgrading Flutter to 3.13.3 from 3.10.6 in /Users/coder/Developer/flutter...
Downloading Darwin arm64 Dart SDK from Flutter engine b8d35810e91ab8fc39ba5e7a41bff6f697e8e3a8...
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed

Building flutter tool...
Resolving dependencies...
Got dependencies.

Upgrading engine...
Downloading android-arm-profile/darwin-x64 tools...              1,274ms
Downloading android-arm-release/darwin-x64 tools...                999ms
Downloading android-arm64-profile/darwin-x64 tools...            1,147ms
Downloading android-arm64-release/darwin-x64 tools...            1,017ms
Downloading android-x64-profile/darwin-x64 tools...              1,179ms
Downloading android-x64-release/darwin-x64 tools...              1,007ms
Downloading android-x86 tools...                                    4.5s
Downloading android-x64 tools...                                    4.4s
Downloading android-arm tools...                                    4.0s
Downloading android-arm-profile tools...                         2,383ms
Downloading android-arm-release tools...                         1,833ms
Downloading android-arm64 tools...                                  4.4s
Downloading android-arm64-profile tools...                       2,602ms
Downloading android-arm64-release tools...                       1,892ms
Downloading android-x64-profile tools...                         2,598ms
Downloading android-x64-release tools...                         1,901ms
Downloading android-x86-jit-release tools...                     2,885ms
Downloading ios tools...                                           14.8s
Downloading ios-profile tools...                                   13.7s
Downloading ios-release tools...                                   14.0s
Downloading Web SDK...                                             17.2s
Downloading package sky_engine...                                  422ms
Downloading flutter_patched_sdk tools...                         1,330ms
Downloading flutter_patched_sdk_product tools...                 1,194ms
Downloading darwin-arm64 tools...                                   9.1s
Downloading darwin-x64/FlutterMacOS.framework tools...             10.0s
Downloading darwin-x64/gen_snapshot tools...                     2,174ms
Downloading darwin-x64-profile/FlutterMacOS.framework tools...         6.0s
Downloading darwin-x64-profile tools...                          1,190ms
Downloading darwin-x64-profile/gen_snapshot tools...             2,119ms
Downloading darwin-x64-release/FlutterMacOS.framework tools...         3.8s
Downloading darwin-x64-release tools...                          1,073ms
Downloading darwin-x64-release/gen_snapshot tools...             1,915ms
Downloading darwin-arm64/font-subset tools...                      587ms

Flutter 3.13.3 • channel stable • https://github.com/flutter/flutter.git
Framework • revision 2524052335 (6 days ago) • 2023-09-06 14:32:31 -0700
Engine • revision b8d35810e9
Tools • Dart 3.1.1 • DevTools 2.25.0

Running flutter doctor...
Doctor summary (to see all details, run flutter doctor -v):
[✓] Flutter (Channel stable, 3.13.3, on macOS 13.5 22G74 darwin-arm64, locale en-US)
[✓] Android toolchain - develop for Android devices (Android SDK version 33.0.2)
[✓] Xcode - develop for iOS and macOS (Xcode 14.3)
[✓] Chrome - develop for the web
[!] Android Studio (version unknown)
    ✗ Unable to determine Android Studio version.
[!] Android Studio (version unknown)
    ✗ Unable to determine Android Studio version.
[✓] Android Studio (version 2022.2)
[!] Android Studio (version unknown)
    ✗ Unable to determine Android Studio version.
[!] Android Studio (version unknown)
    ✗ Unable to determine Android Studio version.
[!] Android Studio (version unknown)
    ✗ Unable to determine Android Studio version.
[✓] IntelliJ IDEA Ultimate Edition (version 2023.2)
[✓] IntelliJ IDEA Ultimate Edition (version 2023.2)
[✓] VS Code (version 1.81.0)
[✓] VS Code (version 1.82.0-insider)
[✓] Connected device (5 available)
    ! Error: To use AppiPhoneX2 for development, enable Developer Mode in Settings → Privacy & Security.  (code 6)
[✓] Network resources

! Doctor found issues in 5 categories.
```

* Run flutter devices

```
==> flutter devices

```
## Scaffold flutter app

```
flutter create unicorn-platform
```

## Develop

```
flutter run -d chrome
```

## Release

```
flutter build web

```