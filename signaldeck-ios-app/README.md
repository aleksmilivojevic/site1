# Signal Deck for iPhone

Signal Deck is a SwiftUI probability, statistics, and quantitative-finance quiz app. It includes configurable quizzes, generated question variants, a learning center, custom cards, personal decks, quiz history, recovery codes, and trophies.

## Screenshots

| Topic selection | Live quiz |
| --- | --- |
| <img src="signal%20deck%20screenshots/play%20topics.png" alt="Signal Deck topic selection" width="390"> | <img src="signal%20deck%20screenshots/live%20quiz%201.png" alt="Signal Deck live expected-value question" width="390"> |

| Correct-answer feedback | Submitted-card review |
| --- | --- |
| <img src="signal%20deck%20screenshots/live%20quiz%202.png" alt="Signal Deck correct-answer feedback" width="390"> | <img src="signal%20deck%20screenshots/live%20quiz%203.png" alt="Signal Deck submitted-card review and worked solution" width="390"> |

| Learning Center | Expanded learning content |
| --- | --- |
| <img src="signal%20deck%20screenshots/learn%201.png" alt="Signal Deck Learning Center topics" width="390"> | <img src="signal%20deck%20screenshots/learn%202.png" alt="Signal Deck expanded Learning Center content" width="390"> |

| Question Creation | User Center |
| --- | --- |
| <img src="signal%20deck%20screenshots/create%201.png" alt="Signal Deck custom question creation center" width="390"> | <img src="signal%20deck%20screenshots/user%201.png" alt="Signal Deck User Center and Trophy Room" width="390"> |

## Requirements

- macOS with Xcode
- iOS 17 or later
- An Apple ID for installing a development build on a physical iPhone

## Run the app

1. Clone or download this repository.
2. Open `SignalDeck.xcodeproj` in Xcode.
3. Select the `SignalDeck` target.
4. Open **Signing & Capabilities**.
5. Choose your own development team.
6. Replace `com.example.signaldeck` with a bundle identifier unique to you.
7. Select an iPhone simulator or connected iPhone.
8. Press **Run**.

## Project structure

- `SignalDeck/ContentView.swift`: SwiftUI interface
- `SignalDeck/WebView.swift`: app state, quiz logic, data models, recovery, and learning-center rendering
- `SignalDeck/AppData.json`: bundled topics and question bank
- `SignalDeck/LearningGuideContent.html`: bundled learning-center reference content
- `SignalDeck/Assets.xcassets`: colors and app icons
- `scripts/`: source and generator for the app icon

## License

Released under the MIT License. See `LICENSE`.
