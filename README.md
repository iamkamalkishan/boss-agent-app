# Boss Agent - Flutter App

## Build Instructions

### Prerequisites
1. Flutter SDK (3.24+)
2. Android SDK
3. Java 17+

### Build APK
```bash
cd /path/to/flutter_app
flutter pub get
flutter build apk --release
```

### APK Location
`build/app/outputs/flutter-apk/app-release.apk`

### Configuration
1. Open `lib/main.dart`
2. Replace `YOUR_API_KEY_HERE` with your Kilo API key
3. Change the model name if needed

### Features
- Chat interface with AI
- Dark theme
- Message bubbles
- Loading indicator
- Error handling

### Notes
- The app uses Kilo Gateway API for AI responses
- Model: kilo-auto/free (free tier)
- Requires internet connection