# 📘 Video 3: Language Translators

To execute a program written in **high-level** or **assembly** language, we need language translators.

---

## 🛠️ Types of Translators

### 1. **Assembler**
- Converts **assembly language** into **machine code**
- Used for low-level languages (with mnemonics like `ADD`, `MOV`, etc.)

---

### 2. **Compiler vs Interpreter**

High-level languages are converted using **either a compiler or an interpreter**.

Here's a clear comparison:

| Feature                 | Compiler                         | Interpreter                         |
|-------------------------|----------------------------------|-------------------------------------|
| Converts                | HLL → Machine Code               | HLL → Machine Code                  |
| Object Code             | ✅ Creates object code (`.exe`)   | ❌ No object code generated         |
| Execution               | After full translation           | Line-by-line during execution      |
| Speed                   | Faster execution                 | Slower execution                   |
| Debugging               | Shows all errors at the end      | Shows errors line-by-line          |
| Source Code Required?   | Not needed after compilation     | Needed every time                  |
| Memory Usage            | More (stores object code)        | Less (no object code stored)       |
| Examples                | C, C++, C#                       | Python, Ruby, Perl                 |

---

## 🧠 Real-world Analogy

- **Compiler** → Like watching a movie with **English subtitles**  
  (Entire script translated and displayed all at once)

- **Interpreter** → Like a **real-time translator** in a meeting  
  (Translates line-by-line as the speaker talks)

---

## 🧾 Example (Compiler Flow)

```c
// first.c
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
