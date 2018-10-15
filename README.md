# Mac App for Drag-n-Drop Upload of APK or IPA Files to Device


## Requirements

For APK files you'll need [_Android Debug Bridge (adb)_](https://developer.android.com/studio/releases/platform-tools.html).
For IPA files you'll need [ideviceinstaller](https://cgit.sukimashita.com/ideviceinstaller.git/), that you can install with `brew install ideviceinstaller`.
And at the end, you'll need _gtimeout_, that is part of Core Utils, and you can install them with `brew install coreutils`.


## Installation

1. Get requirements.
2. Download [_Upload apk to Device.app_](https://gitlab.knoopje.com/aleksandrvin/upload-apk-to-device/raw/master/Upload%20APK%20or%20IPA%20to%20Device.zip)
   to _Applications_.
3. Open _Finder_ with an _apk_ or _ipa_ file, right-click on the file and choose _Get Info_ in context menu.
4. Choose _Open with:_ and select _Other..._, then navigate to _Upload APK or IPA to Device_ in  _Applications_ folder, select _Always Open With_, click _Add_.
   Now you can upload _apk_ and _ipa_ files by just double-clicking on them.
5. Optionally drag _Upload APK or IPA to Device.app_ icon from _Applications_ to your Dock to be able to upload _apk_ and _ipa_ files by dropping them on the
   app icon in the Dock.


## Development

1. Clone repo.
2. Open _Upload APK or IPA to Device.scpt_ in _Script Editor_.
3. Edit Apple Script.
4. Go to _File > Export..._, choose _Application_ as _File Format_ and click _Save_.
5. Go to file _Upload APK or IPA to Device.app_, right-click on it and choose _Show Package Contents_.
6. Go to _Resources_ folder and replace _droplet.icns_ with the one from root of repo.
5. Have fun with _Upload APK or IPA to Device.app_.


## Release

1. After development, compress the _Upload APK or IPA to Device.app_ and commit the _Upload APK or IPA to Device.zip_.
