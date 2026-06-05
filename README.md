# Triplit

A native Android app for tracking shared expenses during trips and splitting the bill at the end.

## What it does

Triplit lets you record every expense as it happens during a vacation with friends or family, then calculates who owes what to whom when the trip is over — minimising the number of transfers needed to settle up.

**Core features (planned)**

- Create a trip and add all participants
- Log expenses: amount, payer, category, and who it covers
- Support partial splits (not every expense involves everyone)
- Automatic debt simplification at settlement time
- Offline-first — no account required
- Export a summary to share with the group

## Tech stack

| Layer | Choice |
|---|---|
| Language | Kotlin |
| Min SDK | 24 (Android 7.0) |
| Target SDK | 36 |
| UI | Jetpack Compose (planned) |
| Persistence | Room (planned) |

## Getting started

1. Clone the repo
2. Open in Android Studio Meerkat or later
3. Run on an emulator or device (API 24+)

## Project structure

```
app/src/main/
├── AndroidManifest.xml
└── res/                  # resources (icons, themes, strings)
```

Source code will live under `app/src/main/java/fr/mandarine/triplit/`.

## License

MIT
