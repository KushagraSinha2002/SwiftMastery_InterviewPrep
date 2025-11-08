# 🧠 SwiftMastery Interview Prep

A structured **Swift Playground** designed to master iOS interview concepts — covering everything from language fundamentals to advanced Swift topics like ARC, closures, concurrency, and architectural patterns.

---

## 🚀 Overview

This repository serves as a **comprehensive Swift interview preparation resource** — implemented entirely as an interactive Xcode Playground.  
Each page focuses on a core concept with:
- Cleanly formatted notes  
- Code examples  
- Interview-ready explanations  
- Reusable snippets  

Whether you’re brushing up before an iOS interview or revising Swift fundamentals, this Playground helps you learn *by running actual code.*

---

## 📘 Topics Covered

| # | Topic | Description |
|---|-------|--------------|
| 01 | **Class vs Struct** | Value vs Reference Types, Mutability, Identity |
| 02 | **ARC & Memory Management** | `weak` vs `unowned`, Retain Cycles, `deinit` |
| 03 | **Closures & Escaping** | Capture Lists, `@escaping` vs Non-Escaping |
| 04 | **Codable** | JSON Encoding/Decoding, Custom Keys |
| 05 | **Concurrency** | `async/await`, `Task`, `MainActor`, Structured Concurrency |
| 06 | **Protocols & Extensions** | Protocol-Oriented Programming |
| 07 | **Error Handling** | `Result` Type, `throws`, `try?`, `try!` |
| 08 | **Swift DSAs** | Arrays, Strings, HashMaps, Sorting, Algorithm patterns |
| 09 | **MVVM Pattern** | Building scalable architecture with separation of concerns |
| 10 | **Quick Revision** | Common iOS interview Q&A Snippets |

---

## 🗂 Playground Structure

```plaintext
SwiftMastery_InterviewPrep.playground
├─ Pages/
│  ├─ 00_Overview
│  ├─ 01_Class_vs_Struct
│  ├─ 02_ARC_Weak_Unowned
│  ├─ 03_Closures_Escaping
│  ├─ 04_Codable_JSON
│  ├─ 05_Concurrency_AsyncAwait
│  ├─ 06_Protocols_Extensions
│  ├─ 07_ErrorHandling_Result
│  ├─ 08_Collection_DSAs
│  ├─ 09_ProjectPatterns_MVVM
│  └─ 10_QuickRevision
│
├─ Sources/
│  ├─ Helpers.swift          # Shared utilities for formatting output
│  └─ Models.swift           # Reusable structs/classes used across pages
│
└─ Resources/
   ├─ sample.json
   ├─ sampleImage.png
   └─ testData.txt
```


- **Pages/** → Each topic as a separate Playground page with notes & examples  
- **Sources/** → Shared helper functions and common models  
- **Resources/** → JSON, media, or data files for practice  

---

## ⚙️ Setup & Usage

1. **Clone the repo**
   ```bash
   git clone https://github.com/KushagraSinha2002/SwiftMastery_InterviewPrep.git

2.	Open in Xcode
	•	Double-click SwiftMastery_InterviewPrep.playground
	•	Choose macOS or iOS Playground environment when prompted
3.	Navigate
	•	Use the left sidebar to switch between topic pages
	•	Run examples directly in Xcode’s live console
4.	Experiment
	•	Modify, extend, or run snippets interactively to reinforce concepts

⸻

🎯 Goal

To create a self-contained Swift reference that helps:
	•	🧩 Revise iOS interview concepts quickly
	•	🧠 Understand real code examples, not just theory
	•	🚀 Build mastery in Swift fundamentals and advanced concepts alike

This Playground doubles as both a learning notebook and a revision companion for serious iOS developers.

⸻

🧰 Tools & Requirements
	•	Xcode 15+
	•	Swift 5.9+
	•	Compatible with macOS & iPad Playgrounds

⸻

💡 Example Snippet (from 01_Class_vs_Struct)
class Dog {
    var name: String
    init(name: String) { self.name = name }
}

struct Cat {
    var name: String
}

var dog1 = Dog(name: "Benny")
var dog2 = dog1
dog2.name = "Max"
print(dog1.name) // Max (Reference Type)

var cat1 = Cat(name: "Whiskers")
var cat2 = cat1
cat2.name = "Fluffy"
print(cat1.name) // Whiskers (Value Type)


🧩 Future Additions
	•	🧵 Async sequences and structured concurrency patterns
	•	🧱 Property wrappers and Combine basics
	•	📦 Swift Package Manager mini-guide
	•	🧠 Practice coding problems (DSA in Swift)

⸻

👨🏻‍💻 Author

Kushagra Sinha
iOS Developer | React Native Engineer | Swift Enthusiast

🌐 kushagrasinha.com￼
💼 LinkedIn￼
📧 kushagrasinha2002@gmail.com

⸻

🪪 License

This project is licensed under the MIT License — you’re free to use, modify, and share it with attribution.

⸻

⭐ If you find this useful, consider starring the repository to support future updates!
