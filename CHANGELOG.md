## 0.3.7+8
* docs change pubspec.yaml description

## 0.3.7+7
* docs Better English documentation

## 0.3.7+6
* docs better example

## 0.3.7+5
* docs better example

## 0.3.7+4
* docs better example

## 0.3.7+3
* docs deleteAllCache api return whether the boolean value is deleted

## 0.3.7+2
* fix `ios` path problem
* fix `ios` deleteAllCache functional repair
* docs `document` deleteAllCache api description
* fix `android` ffmpeg keep metadata orientation by -noautorotate command

## 0.3.7+1
* feat `both` add api deleteAllCache to delete cache, please do not put other things in the folder of this plugin, it will be cleared

## 0.3.7
* **Breaking change** `both` rename startCompress to compressVideo, stopCompress to cancelCompression
* feat `both` compressVideo api add params { int startTime, int duration, bool includeAudio, int frameRate }
* feat `both` getMediaInfo returns add orientation
* fix `android` getMediaInfo returns height and width flipped
* fix `android` different quality compression size
* style `example` fixed some problems with example

## 0.3.6
* docs `document` ios swift version documents of how to fix Regift
* refactor `android` reduce compressing time
* refactor `android` remove updateProgress redundant code to improve performance
* refactor `dart` change all print to debugPrint to improve release performance

## 0.3.5+4
* Support latest dependencies

## 0.3.5+3
* update documents

## 0.3.5+2
* increased swift version to 5.0

## 0.3.5+1
* reduced frame rate to 15 on android, use milliseconds for duration

## 0.3.5
* **Breaking change** fix The old version does not scale the Android compressed video,
  That is, the startCompress `quality` properties has no effect.
* fix IOS pod dependency `Regift`
* feat enum `VideoQuality` add DefaultQuality, startCompress `quality` Use the default properties of the old version
* fix IOS convertVideoToGif file Suffix
* docs update example

## 0.3.4+1
* fix example lost the IOS pod dependency `Regift`

## 0.3.4
* docs update convertVideoToGif associated document
* feat Created API for conversion of video files to gif with start time
  and duration parameters.
  For Android ffmpeg is used for conversion and for iOS Regift
  library is used.
  Also, added an example on how to use the API within example project.

## 0.3.3+3
* docs update README.md

## 0.3.3+2
* docs update README.md

## 0.3.3+1
* docs docs folder to doc

## 0.3.3
* docs international documentation increased

## 0.3.2
* fix unsubscribe excess stream error

## 0.3.1
* fix compressed video is null
* fix Bad state: Stream has already been listened to
* fix Video same address cannot be compressed for the second time

## 0.3.0
* **Breaking change** refactor ios anderoid lib code
* feat add getThumbnailWithFile and getMediaInfo api
* fix android private folder permissions cause possible problems
* change startCompress api return type

## 0.2.0+9
* doc update document

## 0.2.0+8
* doc update document

## 0.2.0+7
* fix ios getThumbnail path error
* Better tips of Compressing error
* **Breaking change** start Compress api add whether to cancel the parameter

## 0.2.0+6
* chore update swift 5

## 0.2.0+5
* fix: fix the wrong Usage

## 0.2.0+4
* fix: add some suggestions for reduce apk size
* **Breaking change** compressVideo api renamed startCompress
* feat: add stopCompress api
* update README.md

## 0.2.0+3
no change

## 0.2.0+2
* fix: IOS fix import AVFoundation

## 0.2.0+1
* fix: Android video type changed h264

## 0.2.0
* **Breaking change** Migrated dependent sdk, Upgraded kotlin and gradle versions
* fix: solved Android transcoding video error code 8
* update example/README.md

## 0.1.7
* docs: Better Readme

## 0.1.6
* docs: Better documentation

## 0.1.5
* CHANGELOG.md
* fix: supported x86 arm64-v8a armeabi armeabi-v7a

## 0.1.4
* fix:gradle config 'compile' replaced with 'implementation'

## 0.1.3
* fix: fix ios 4.2 version bugs

## 0.1.2
* fix: fix ios build swift_version

## 0.1.1
* chore: update `AndroidX`

## 0.1.0

* feature: get vedio thumbnail
* feature: compress vedio
