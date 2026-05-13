# Ghosty

A personal Flutter music player.

This is a private fork of [BrightDV/BlackHole](https://github.com/BrightDV/BlackHole) (itself originally [Sangwan5688/BlackHole](https://github.com/Sangwan5688/BlackHole) by Ankit Sangwan), kept under GPL v3.

## Platforms

Built and tested on Android (Pixel 9a emulator). Other targets (iOS, macOS, Windows, Linux) are configured but not currently verified.

## Toolchain

- Flutter 3.41.6 (Dart 3.10+)
- Android Gradle Plugin 8.9.2
- Gradle 8.11.1
- Kotlin 1.9.22
- NDK 28.2.13676358
- minSdk 28, targetSdk 35

## Setup

```bash
# 1. Install Flutter dependencies
flutter pub get

# 2. Create your local secrets file (gitignored)
cp lib/Services/secrets.example.dart lib/Services/secrets.dart
# Then edit secrets.dart and set ytMusicApiKey to the public YouTube Music
# web client key. It's the same value used by every unofficial YT Music client
# (literally hardcoded in YT Music's HTML).

# 3. Run on a connected device / emulator
flutter run
```

## Identifiers

- Application ID (Android): `com.ghosty.app`
- Bundle ID (iOS): `com.ghosty.app`
- URL scheme: `ghosty://`
- Pubspec name: `ghosty`

## License

GPL v3, inherited from upstream. See [`LICENSE`](LICENSE). Source files retain
the original copyright header attributing Ankit Sangwan / BlackHole, as
required by the GPL.
