# 📘 Video 2: Low-Level vs High-Level Languages

C programming is written in a **high-level language**, but to understand it better, we first need to know the difference between **low-level** and **high-level** languages.

## 🧠 Low-Level Language

Low-level languages are close to the hardware and difficult for humans to understand.

### ➤ Machine Language
- Written in binary (0s and 1s).
- Directly understood by the computer.
- Hard for humans to read or write.
- Example: instructions sent to OS or system software.
- Humans find it almost impossible to work with.

> 🧊 Box shown in video: **Machine Language ➝ OS/System Software**
> 
> 🤯 Hard to understand for humans.

### ➤ Assembly Language
- Uses mnemonic codes like `ADD`, `MOV`, `SUB`.
- Slightly easier than binary, but still hard for beginners.
- Still hardware-specific and not portable.
- Requires an assembler to convert it to machine code.

> 📦 Box shown: `ADD`, `MOV`, `SUB` — easier than machine language, but still low-level.

---

## 💡 High-Level Language

High-level languages are easy for humans to read and write.

- Example: `1 + 1 = 2`
- Easy to understand and write.
- Portable and not tied to a specific machine.
- Needs a **compiler** or **interpreter** to convert into machine code.

```c
int result = 1 + 1;
