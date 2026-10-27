# Social Analyzer Android WebView Wrapper

This repository contains a minimal Android app that loads a web app URL in a `WebView`.

## Default URL
The app loads:

`http://localhost:9005/app.html`

Change this in:

`app/src/main/res/values/strings.xml`

Example:

```xml
<string name="web_app_url">https://your-domain.example.com/app.html</string>
```

## Open in Android Studio
1. Open this folder in Android Studio.
2. Let Gradle sync complete.
3. Connect an Android device or start an emulator.
4. Run the app.

## Build APK
From Android Studio:
- Build > Build Bundle(s) / APK(s) > Build APK

## Notes
- This wrapper does not compile the original Node.js app into native Android code.
- It loads the web app URL in a mobile browser-like container.
- For a local development environment, use `http://localhost:9005/app.html` only while the web app is running on your machine.
- For production use, point it to a hosted web app URL.
