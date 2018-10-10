# Mac App for Drag-n-Drop Upload of APK to Device


## Requirements

You'll need [_Android Debug Bridge (adb)_](https://developer.android.com/studio/releases/platform-tools.html) and to `brew install coreutils` for _gtimeout_.


## Installation

1. Get requirements.
2. Download [_Upload apk to Device.app_](https://gitlab.knoopje.com/aleksandrvin/upload-apk-to-device/raw/master/Upload%20apk%20to%20Device.zip) to _Applications_.
3. Open _Finder_ with and _apk_ file, right-click on the file and choose _Get Info_ in context menu.
4. Choose _Open with:_ and select _Other..._, then navigate to _Upload apk to Device_ in  _Applications_ folder, select _Always Open With_, click _Add_. Now you can upload _apk_ files just by double-clicking on them.
5. Optionally drag _Upload apk to Device.app_ icon from _Applications_ to your Dock to be able to upload _apk_ files by dropping them on the app icon in the Dock.


## Development

1. Clone repo.
2. Open _Upload apk to Device.scpt_ in _Script Editor_.
3. Edit Apple Script.
4. Go to _File > Export..._, choose _Application_ as _File Format_ and click _Save_.
5. Have fun with _Upload apk to Device.app_.
