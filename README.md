# SonoTuner

Introducing SonoTuner — a musician’s dream.
A sleek, accurate, and intelligent tuner built with Flutter, designed to make tuning effortless.
From guitars to violins, SonoTuner listens, detects, and guides you to perfect pitch — fast, smooth, and beautifully visualized.

## Why SonoTuner?

Tuning shouldn’t feel like a chore. SonoTuner turns it into a satisfying experience.
With its auto-detect tuning, real-time pitch feedback, and custom tuning creation, this app bridges professional accuracy with everyday usability — whether you’re just starting out or fine-tuning before a performance.

## Key Features
### YIN-Powered Pitch Detection

SonoTuner uses the YIN algorithm (via the pitch_detector_dart library) — a proven and efficient method for identifying the fundamental frequency of a sound.
From a mix of musical notes and background noise, YIN smartly locks onto periodic signals (actual notes) and ignores random noise, ensuring the tuner reacts only to real, playable tones.
The result: fast, stable, and reliable pitch detection every time you pluck a string.

### Auto-Tuning Mode

Let SonoTuner do the work.
Just start playing, and the app:
  - Detects which string you’re tuning.
  - Analyzes the pitch in real time.
  - Tells you whether you’re flat or sharp.
  - Celebrates with a subtle animation when you’re perfectly in tune.

No manual selection, no guesswork — just play and tune.

### Manual Mode

Prefer full control? Switch to manual mode, tap any string, and focus solely on that note. Perfect for detailed fine-tuning or non-standard setups.

### Custom Tunings

Every musician has a unique sound — SonoTuner lets you create yours.
Define your own tuning by selecting notes and octaves for each string, give it a name, and save it.
You can edit, delete, and switch between tunings anytime.

### Multi-Instrument Support

SonoTuner comes preloaded with tunings for multiple instruments:
  - Guitar – Standard, Drop D, Open G, Open D, Open C
  - Bass – Standard, Drop D, Drop C, Half Step, Full Step
  - Ukulele – Standard, Traditional, Low G, Baritone, Slack Key
  - Violin – Standard, Baroque, High G, Drop D, Cross Tuning

Each instrument has realistic visuals and easy preset switching.

### Clean, Intuitive Interface
  - Simple circular indicators for string selection and tuning status
  - Smooth animations and visual feedback when a string is perfectly tuned
  - Minimal, distraction-free design built with Flutter’s Material UI principles

### Technical Overview
- Framework: Flutter (Dart)
- Pitch Detection: pitch_detector_dart (YIN algorithm)
- Audio Capture: flutter_audio_capture
- Permissions: permission_handler

Real-time feedback via frequency-to-note mapping and cent deviation calculation

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/sonotuner.git
   cd sonotuner
2. Install Dependancies:
   `flutter pub get `
3. Run the app:
   `flutter run `

### Project Structure
  lib/
  ├── main.dart # Core logic and UI
  assets/
  ├── images/ # App and instrument visuals
  pubspec.yaml # Dependencies and configuration

