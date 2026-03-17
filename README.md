# InterviewFlashcards

iOS flashcard app for senior Swift & iOS interview prep. 119 cards across four categories — tap to flip, swipe to advance, shuffle to randomize.

Built with SwiftUI. Requires Xcode 15+, iOS 17+.

---

<p align="center">
  <video src="https://github.com/christopherkmoore/InterviewFlashcards/raw/main/demo.mp4" autoplay loop muted playsinline width="320"></video>
</p>

---

## Categories

| Category | Cards | Topics |
|----------|-------|--------|
| **Swift** | 45 | Optionals, closures, protocols, generics, ARC, error handling, property wrappers, enums |
| **Concurrency** | 41 | Actors, async/await, data races, deadlocks, task cancellation, Sendable, GCD, Combine |
| **SwiftUI** | 26 | State management, view lifecycle, NavigationStack, performance, @Observable |
| **Testing** | 16 | Swift Testing, XCTest, dependency injection, async testing, parameterized tests |

## Features

- **Tap to flip** — question side (blue) flips to answer (green) with a 3D rotation animation
- **Swipe to advance** — drag left to move to the next card with a stacked card preview effect
- **Category filter** — study all 119 cards or drill into a single topic
- **Shuffle** — randomize card order within the selected category
- **Progress bar** — shows X / N and a progress bar across the top
- **Back navigation** — step back through previously seen cards

## Getting Started

```bash
git clone https://github.com/christopherkmoore/InterviewFlashcards.git
cd InterviewFlashcards
open InterviewFlashcards.xcodeproj
```

Or regenerate with XcodeGen:

```bash
brew install xcodegen && xcodegen generate
```
