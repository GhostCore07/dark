dark
====

Dart / WebGL Doom level renderer.

MINIMIALIST UPDATE
---

### Changes:
- Updated to work with Dart 2 SDK
- Fixed old constant references (PI and GL) to the correct new ones
- Disabled null safety check
- Updated dependency versions to latest
- Fixed rotation error due to change in vector_math dependency
- Added null check for source that was causing a crash
- Tested with IntelliJ IDEA Ultimate with Dart support and Dart SDK 2.16.2
- Tested with Chrome 100.0 and Firefox 99.0

### Building:
- Install Dart SDK
- Open project folder in IntelliJ IDEA Ultimate with Dart add on
- Open pubspec.yaml
- Click Enable Dart support
- Click Pub get
- Click Webdev Build... then Build
- From Run menu click Edit Configurations... then Add New... Dart Web then HTML file: dark.html then OK
- Click Run
- Sometimes you have to refresh the first time it loads (caching issue?)