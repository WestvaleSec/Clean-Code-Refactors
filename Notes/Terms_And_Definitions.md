# 📘 Terms & Definitions

A simple glossary of programming and refactoring terms used throughout this repository.  
Created to help other learners (like myself when I started) understand the core ideas behind *clean code* and *software craftsmanship*.

---

## ⚔️ Kata
A **code kata** is a small, structured programming exercise designed for *practice and repetition*, much like a martial arts kata.  
You solve the same problem multiple times to refine your technique, improve readability, and master clean code habits.  

**Example:**  
The *Gilded Rose Kata* challenges you to refactor messy inventory code while keeping all behavior intact.

---

## 💀 Code Smell
A **code smell** is a surface indication that something might be wrong in your code’s structure — not a bug, but a sign that the code could become harder to maintain or extend in the future.  

**Examples:**  
- **Long Method:** One method does too many things.  
- **Large Class:** A class takes on multiple responsibilities.  
- **Feature Envy:** One class heavily depends on another’s data.  

**Goal:** Identify these “smells” early and refactor them into cleaner, simpler designs.

---

## 🧩 Refactoring
**Refactoring** means improving the internal structure of existing code *without changing what it does*.  
The purpose is to make code cleaner, easier to understand, and safer to modify.

**Common Techniques:**
- Extract Method (split long methods into smaller ones)
- Rename Variable (make names more meaningful)
- Replace Conditional with Polymorphism
- Remove Dead Code

---

## 🧠 SOLID Principles
A set of five design principles for writing maintainable, scalable software:

| Principle | Summary |
|------------|----------|
| **S** – Single Responsibility | A class should have one reason to change. |
| **O** – Open/Closed | Open for extension, closed for modification. |
| **L** – Liskov Substitution | Subclasses should be replaceable by their base classes. |
| **I** – Interface Segregation | Prefer small, focused interfaces over large ones. |
| **D** – Dependency Inversion | Depend on abstractions, not concrete implementations. |

---

## ⚙️ Design Pattern
A **design pattern** is a reusable, general solution to a common programming problem.  
It’s not code you copy-paste, but a *template* for solving similar challenges.

**Examples:**
- Singleton  
- Factory  
- Observer  
- Strategy  
- Decorator  

---

## 🧱 DRY, KISS, and YAGNI
| Acronym | Meaning | Purpose |
|----------|----------|----------|
| **DRY** | *Don’t Repeat Yourself* | Avoid duplicating code or logic. |
| **KISS** | *Keep It Simple, Stupid* | Prefer straightforward, readable solutions. |
| **YAGNI** | *You Aren’t Gonna Need It* | Don’t add functionality until it’s actually needed. |

---

## 🧮 Test-Driven Development (TDD)
A software practice where you:
1. Write a **failing test** first,  
2. Write just enough code to make it **pass**,  
3. **Refactor** for clarity,  
4. Repeat.  

This ensures your code is correct, modular, and easy to maintain.

---

## 📚 Additional Terms
| Term | Definition |
|------|-------------|
| **Legacy Code** | Old code that lacks tests or modern structure but still works. |
| **Encapsulation** | Hiding internal details and exposing only what’s necessary. |
| **Polymorphism** | Different classes can be treated through a common interface. |
| **Abstraction** | Simplifying complex systems by focusing on key details. |

---

### 💬 About
Created by **Zane Cotten** to make clean code and refactoring concepts more approachable for beginners and lifelong learners alike.

---

_Created with ChatGPT assistance and reviewed by me for accuracy… allegedly._
