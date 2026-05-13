# Ghosty

Personal workspace containing the **Ghosty** Flutter music player — a private fork of [BrightDV/BlackHole](https://github.com/BrightDV/BlackHole) (originally [Sangwan5688/BlackHole](https://github.com/Sangwan5688/BlackHole)).

## Structure

```
.
├── Ghosty/        # The Flutter app — see Ghosty/README.md for build instructions
└── README.md      # (this file)
```

## Quick start

```bash
cd Ghosty
cp lib/Services/secrets.example.dart lib/Services/secrets.dart
# fill in the YT Music key (see Ghosty/README.md)
flutter pub get
flutter run
```

## License

The `Ghosty/` app is GPL v3 (inherited from upstream BlackHole). See `Ghosty/LICENSE`.
