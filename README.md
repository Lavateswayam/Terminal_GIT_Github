# Terminal_GIT_Github
First time exploring Git and github with terminal of vs code for learning purpose. Learning Git commands..!!

- # 2026-11-18: Git, GitHub and Terminal Basics

## Git & GitHub

### What is Git?
- Git is a **Version Control System**.
- It is a tool that helps track changes in code.
- It is also a skill you need to learn to use.
- **Commit** means saving changes. (extra: a snapshot of your project at that moment)

### README.md
- `README.md` is a **Markdown file**.
- It is used to write about your project.

---

## The Terminal

- Using the terminal is very efficient, rather than keyboard & mouse.

### Different terms
- Command Line :  The general idea of controlling a computer by typing commands.
- Terminal : The window where you type. It is just the display and input.
- Console : Same as terminal. 
- Shell : The program inside that window that reads your command and runs it.
- Bash, Z-shell (zsh) : This are some popular shells used in day todays life.

### Basic commands
| Command | Meaning |
|---|---|
| `ls` | list files (show my files) |
| `pwd` | print working directory (where am I?) |
| `clear` | clear the screen |

---

## Navigation

| Command | Meaning |
|---|---|
| `cd` | change directory |
| `cd ..` | go back one level from the working directory |
| `cd ~` | home directory |
| `cd /` | root directory |

- The terminal has **autocomplete / suggestions**, which you use with the **Tab** key.

---

## Making Directories

- `mkdir` = make directory (creates a folder)

```bash
mkdir my-folder
```

---

## Flags

- Flags are characters we pass with commands to modify their behaviour.

```bash
ls -l
ls -a
ls -la
```
- (extra) `-l` shows a detailed long list, `-a` shows hidden files too, and `-la` does both.

### Manual command
- `man ls` gives info about the `ls` command.
- `man mkdir` gives info about the `mkdir` command.
- (extra) Press `q` to exit the manual.

