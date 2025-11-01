# WordScramble (SwiftUI)

A SwiftUI word game built as part of [Paul Hudson’s *100 Days of SwiftUI*](https://www.hackingwithswift.com/100/swiftui), Project 5 — *Word Scramble*.  
Players create valid English words from a random root word, with validation powered by `UITextChecker`.

## 🧩 Features
- Declarative SwiftUI architecture with `@State` for reactive updates  
- Real-time validation checks:
  - **Originality** — prevents duplicate words  
  - **Possibility** — ensures letters come from the root word  
  - **Reality** — confirms valid English words using `UITextChecker`  
- Animated insertion of new words  
- Restart button to load a new root word  
- Simple scoring system and clear error alerts  

## 🎯 Learning Outcomes (TPM Perspective)
As part of my TPM upskilling journey, this project demonstrates:
- Understanding **SwiftUI’s declarative UI model**  
- Working with **state management** and event-driven views  
- Bridging **UIKit APIs** (e.g., `UITextChecker`) into SwiftUI  
- Using **Xcode Source Control** and **GitHub integration** effectively  
- Communicating **technical design and trade-offs** between UI and data logic — key TPM fluency  

## 🧠 Concepts Learned
- Swift fundamentals (`guard`, `@State`, closures)  
- UI structure with `NavigationStack`, `List`, and `TextField`  
- Data validation and file reading from bundles (`start.txt`)  
- Clean error handling with alerts and view state  
- Modern Git + GitHub workflow from Xcode and CLI  

## 🚀 Getting Started
1. Clone the repo:
   ```bash
   git clone https://github.com/rdowning07/WordScramble.git

Open WordScramble.xcodeproj in Xcode 16+

Press Run ▶️ to play!

📚 Reference

Based on Paul Hudson’s Project 5: Word Scramble

from the 100 Days of SwiftUI course on Hacking with Swift
.

🧾 License

MIT License 
