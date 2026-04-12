# Codex Agent Demo – Student Instructions

## 🎯 Goal
Use Codex to:
- fix bugs
- generate programs
- follow persistent AI behavior rules

---

## If You Just Completed Setup

If you just completed the setup guide, Codex should already be running from your Downloads folder.

Go directly to [Step 4 — Use the Demo Folder](#-step-4--use-the-demo-folder).

If Codex is not already running, start at [Step 2 — Open Terminal](#-step-2--open-terminal).

---

## 📁 Step 1 — Download and Unzip

Download the demo files here: [demo-files.zip](demo-files.zip)

1. Download `demo-files.zip`
2. Unzip it into your **Downloads** folder
3. The unzipped folder should be named `demo-files`

---

## ⚙️ Step 2 — Open Terminal

### Mac:
- Open **Terminal**

### Windows:
- Open **PowerShell**

---

## 📂 Step 3 — Go to Downloads

### Mac:
```
cd ~/Downloads
```

### Windows:
```
cd $HOME\Downloads
```

If that does not work on your computer, open your Downloads folder and copy its path.

---

## 📂 Step 4 — Use the Demo Folder

If Codex is already running, type this in Codex:

```
change into the demo-files folder and use AGENTS.md for this demo
```

If Codex is not already running, type this in Terminal or PowerShell:

```
cd demo-files
```

---

## ⚙️ Step 5 — Start Codex

Only do this step if Codex is not already running.

### Mac:
```
codex
```

### Windows:
```
codex.cmd
```

Sign in with ChatGPT if prompted

If Codex asks whether you trust the files in this folder, choose to trust them.

If Codex asks you to choose a sandbox, choose the **non-admin** option.

---

## 🧠 Step 6 — Understand the Files

List the files:

```
ls
```

You should see:
```
AGENTS.md
bug.cpp
numbers.txt
```

👉 **AGENTS.md controls how the AI behaves**

---

## 🐛 Step 7 — Fix a Bug

```
fix the bug in bug.cpp
```

---

## 📊 Step 8 — Generate a Program

```
create a C++ program named average.cpp that reads numbers.txt and prints the average
```

---

## 💻 Step 9 — Open the Program in an IDE

### Mac:
In Codex, type:

```
open average.cpp in xcode
```

### Windows:
In Codex, type:

```
open average.cpp in visual studio
```

If Codex cannot open the IDE, open `average.cpp` manually.

---

## 🔁 Step 10 — Modify the Program

```
modify the program to also print the maximum number
```

---

## 🧠 Key Idea

```
Prompt = what you want now
AGENTS.md = how the AI behaves always
```

---

## ⚠️ Important Reminder

AI can make mistakes.

Always:
- read the output
- test the code
- verify correctness
- understand what it did

---

## ✅ You Are Ready

You are now using Codex as an **agentic AI system**
