# XO Game

A two-player tic-tac-toe (X and O) game with score tracking, built with Flutter.

## Overview

The app presents a 3x3 board on which two players take turns placing X and O on the same device. After each move the game checks the row, column and both diagonals of the move for a win. A dialog announces the winner or a draw, the board is cleared, and a running score for each player is kept until it is reset.

## Key features

- Local two-player play on a single device, starting with X.
- An icon above the board shows whose turn is next.
- Win detection on rows, columns and both diagonals, plus draw detection when the board is full.
- Dialogs announcing the winner ("<player> won") or a draw.
- O and X scores kept across rounds within a session.
- Reset button that clears both scores and the board.

## Tech stack

- Flutter (Material design) and Dart (SDK constraint `>=2.17.6 <3.0.0`)
- `cupertino_icons` and `flutter_lints` (see `pubspec.yaml`)
- Platform scaffolding for Android, iOS, web, Linux, macOS and Windows

## Repository structure

```
lib/main.dart        Application code: UI, game state and win checking
test/                Default Flutter template test (not updated for this app)
pubspec.yaml         Dart/Flutter package manifest
android/ ios/ web/   Platform-specific project files
linux/ macos/ windows/
```

## Installation

Install the [Flutter SDK](https://docs.flutter.dev/get-started/install), then:

```bash
git clone https://github.com/Ziyad-HF/X_O_game-.git
cd X_O_game-
flutter pub get
```

## Usage

```bash
flutter run            # run on a connected device or emulator
flutter run -d chrome  # run in the browser
```

Tap an empty square to place the current player's mark. Use the Reset button to clear scores and start over.

## Data

The game uses no external data.

## Team / credits

- Ziyad ElFayoumy ([Ziyad-HF](https://github.com/Ziyad-HF)), sole author.

## License

Released under the MIT License. See [LICENSE](LICENSE).

## Contact

LinkedIn: [Ziyad ElFayoumy](https://www.linkedin.com/in/ziyad-el-fayoumy)
