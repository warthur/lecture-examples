# Codex CLI – Windows Setup Guide (Classroom Version)

## 🎯 Goal
By the end of this guide, you will:
- Install Codex CLI
- Sign in
- Open your Downloads folder in PowerShell
- Be ready to use Codex

---

## ⚠️ Before You Start

You will need:
- A ChatGPT account (free or paid)

At the time these instructions were written, a free ChatGPT account should be enough for this demo.
If Codex access is unavailable, ask your instructor before continuing.
We are using OpenAI Codex because it has the easiest minimum setup at this time.

Codex works best on Windows 11. A recent, fully updated Windows 10 computer may work, but older Windows 10 computers are more likely to have problems.

---

## Create a Free ChatGPT Account

1. Go to https://chatgpt.com
2. Click **Sign up**
3. Create an account using email, Google, Apple, or Microsoft
4. Complete the verification steps if prompted
5. Stop once you can sign in to ChatGPT in your browser

---

## ⚙️ Step 1 — Open PowerShell

1. Click the **Start Menu**
2. Type: `PowerShell`
3. Click **Windows PowerShell** or **PowerShell**

You should see something like:

```
PS C:\Users\YourName>
```

---

## ⚙️ Step 2 — Check if Codex Is Already Installed

In PowerShell, type:

```
codex.cmd --version
```

Press Enter

### ✅ If you see a version number
Example:
```
codex-cli 0.97.0
```

👉 Skip to Step 6

---

### ❌ If you see "not recognized"
👉 Continue to Step 3

---

## ⚙️ Step 3 — Check if Node.js Is Installed

In PowerShell, type:

```
node -v
```

Press Enter

Then type:

```
npm.cmd -v
```

Press Enter

---

### ✅ If you see version numbers
Example:
```
v20.x.x
10.x.x
```

👉 Continue to Step 5

---

### ❌ If you see "not recognized"
👉 You need to install Node.js → go to Step 4

---

## ⚙️ Step 4 — Install Node.js

1. Go to:
   https://nodejs.org

2. Download the **LTS version**

3. Run the installer

4. Follow all installation steps

---

### 🔁 After installing:
1. Close PowerShell
2. Reopen PowerShell
3. Run again:

```
node -v
npm.cmd -v
```

👉 Make sure both commands show version numbers

---

## ⚙️ Step 5 — Install Codex CLI

In PowerShell, run:

```
npm.cmd install -g @openai/codex
```

Wait for installation to complete

---

## ⚙️ Step 6 — Verify Codex Installation

Run:

```
codex.cmd --version
```

You should see a version number

---

### ❌ If you see "not recognized"
- Close PowerShell
- Reopen it
- Try again

If it still does not work, the installation may not have completed successfully.

---

## ⚙️ Step 7 — Open Your Downloads Folder

In PowerShell, type:

```
cd $HOME\Downloads
```

Press Enter

---

## ⚙️ Step 8 — Start Codex

Run:

```
codex.cmd
```

---

## ⚙️ Step 9 — Sign In

When prompted, choose:

👉 **Sign in with ChatGPT**

Follow the browser login steps

---

## ⚙️ Step 10 — Sandbox Setup

If prompted to choose a sandbox:

👉 Choose the **non-admin** or **unelevated** option if you do not have administrator access.

The exact wording may vary slightly.

---

## ⚙️ Step 11 — Continue to the Demo

Codex should now be running from your Downloads folder.

Continue to the demo instructions.

---

## ⚠️ Common Issues

### "node is not recognized"
→ Node.js is not installed correctly

---

### "npm.ps1 cannot be loaded because running scripts is disabled"
→ Use `npm.cmd` instead of `npm`

---

### "codex is not recognized"
→ Install Codex first, then restart PowerShell if needed

---

### "codex.ps1 cannot be loaded because running scripts is disabled"
→ Use `codex.cmd` instead of `codex`

---

### Login problems
→ Make sure you completed browser login

---

### Install errors
→ If `npm.cmd install -g @openai/codex` fails, ask your instructor for help before continuing

---

## Next Step

[Continue to the Agent Demo](agent_demo.md)

[Back to AI Demo Overview](index.md)
