# 🧹 Clean Code Refactors

A collection of refactoring exercises, katas, and experiments designed to strengthen my understanding of **clean code**, **SOLID principles**, and **software craftsmanship** in C#.

Each exercise begins with intentionally messy, unstructured, or inefficient code and is refactored into something cleaner, simpler, and easier to maintain — while preserving functionality.

📖 See also: [Terms & Definitions](./Notes/Terms_And_Definitions.md)

---

## 🧭 Purpose

This repository serves as my **code-cleaning playground**, where I practice:
- Identifying and correcting **code smells**
- Applying **refactoring techniques** from *Clean Code* and *Refactoring (Fowler)*
- Maintaining readability and testability
- Adhering to the **SOLID principles**
- Transforming procedural, rigid code into modular, reusable design

---

## 📂 Repository Structure

| Folder | Description |
|--------|-------------|
| **Refactoring_Katas/** | Structured refactoring challenges from classic exercises like Gilded Rose and Tennis Game |
| **Code_Smells_Practice/** | Targeted drills for fixing specific smells (Long Methods, Feature Envy, etc.) |
| **Real_World_Cleanup/** | Practice cleaning up messy or legacy-style real-world code |
| **Notes/** | Personal documentation, insights, and reading summaries from Clean Code & Refactoring books |

<pre>
Clean-Code-Refactors/
├── README.md
│
├── Refactoring_Katas/
│   ├── Gilded_Rose/
│   │   ├── Before.cs
│   │   ├── After.cs
│   │   └── Notes.md
│   └── Tennis_Game/
│       ├── Before.cs
│       ├── After.cs
│       └── Notes.md
│
├── Code_Smells_Practice/
│   ├── Long_Method/
│   │   ├── Before.cs
│   │   ├── After.cs
│   │   └── Notes.md
│   ├── Feature_Envy/
│   │   ├── Before.cs
│   │   ├── After.cs
│   │   └── Notes.md
│   ├── Large_Class/
│   │   ├── Before.cs
│   │   ├── After.cs
│   │   └── Notes.md
│   └── Notes.md
│
├── Real_World_Cleanup/
│   ├── ExampleProject_Before/
│   ├── ExampleProject_After/
│   └── Notes.md
│
└── Notes/
    ├── SOLID_Principles.md
    ├── Code_Smells_List.md
    ├── Refactoring_Techniques.md
    └── Reading_Notes.md
</pre>

---

## 🧩 Example Format for Each Exercise

<pre>
Long_Method/
├── Before.cs     # Original unrefined code
├── After.cs      # Clean, refactored version
└── Notes.md      # What was changed, why, and what improved
</pre>

Example `Notes.md`:
```markdown
### 🧠 Problem
This class contains a single, 120-line method with multiple responsibilities.

### 🔧 Refactoring
- Extracted smaller private methods for logical chunks.
- Introduced early returns for clarity.
- Improved naming consistency.

### ✅ Result
Reduced complexity, improved readability, easier to unit test.

```

---

## 📘 Learning Resources
| Resource                                                                               | Description                                                 |
| -------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| [Refactoring.Guru](https://refactoring.guru)                                           | Reference for code smells and common refactoring techniques |
| [Emily Bache’s Refactoring Katas](https://github.com/emilybache/Refactoring-Katas)     | Classic katas like Gilded Rose and Tennis Game              |
| [The Gilded Rose Kata (C#)](https://github.com/emilybache/GildedRose-Refactoring-Kata) | The most famous refactor challenge                          |
| [Codewars](https://www.codewars.com)                                                   | Source of small, messy code solutions to clean up           |
| [Exercism C# Track](https://exercism.org/tracks/csharp)                                | Browse community solutions and practice improving them      |
| *Clean Code* – Robert C. Martin                                                        | Foundational refactoring principles                         |
| *Refactoring: Improving the Design of Existing Code* – Martin Fowler                   | Deep dive into design-improving techniques                  |

---

## 🧠 Key Topics Practiced
| Category                        | Focus Areas                                                                                                                                            |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Code Smells & Anti-Patterns** | Long Method<br>Large Class<br>Feature Envy<br>Duplicated Code<br>Primitive Obsession<br>Inappropriate Intimacy                                         |
| **Refactoring Techniques**      | Extract Method / Class / Interface<br>Replace Conditional with Polymorphism<br>Introduce Parameter Object<br>Remove Dead Code<br>Simplify Nested Logic |
| **Principles Applied**          | SOLID<br>DRY<br>YAGNI<br>KISS<br>Composition over Inheritance                                                                                          |

---

## 🧾 Progress Tracker
| Category                 | Exercises                              | Status         |
| ------------------------ | -------------------------------------- | -------------- |
| **Refactoring Katas**    | Gilded Rose, Tennis Game               | ⚪ Planned |
| **Code Smells Practice** | Long Method, Large Class, Feature Envy | ⚪ Planned      |
| **Real World Cleanup**   | TBD                                    | ⚪ Planned      |

---

## 🪪 License

This repository is licensed under the MIT License.

---

## 💬 About

Created and maintained by Zane Cotten — a developer focused on writing clean, maintainable C# code that emphasizes clarity, simplicity, and scalability.

Generated by ChatGPT, reviewed and edited by me (Zane Cotten) for accuracy.
