# Chess Coordinate Trainer

A mobile-first chess coordinate trainer designed for Google Chrome on Android.

## Voice input
The app uses the browser's Web Speech API. Chrome will ask for microphone permission when voice input is started.

For microphone access, serve the app over HTTPS (or run it on localhost). Opening `index.html` directly as a `file://` page may not allow microphone access.

## Use
1. Choose White or Black orientation.
2. Tap Start Training.
3. A random square is highlighted.
4. Tap "Say the square" and say e.g. "E four".
5. Correct answers automatically advance to another random square.

## Deploy
Upload `index.html` to any HTTPS static web host. It requires no server-side code.
