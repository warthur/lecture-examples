# Codex CLI – Mac Setup Guide (Classroom Version)

## 🎯 Goal
By the end of this guide, you will:
- Install Codex CLI
- Sign in
- Open your Downloads folder in Terminal
- Be ready to use Codex

---

## ⚠️ Before You Start

You will need:
- A ChatGPT account (free or paid)

At the time these instructions were written, a free ChatGPT account should be enough for this demo.
If Codex access is unavailable, ask your instructor before continuing.
We are using OpenAI Codex because it has the easiest minimum setup at this time.

---

## Create a Free ChatGPT Account

1. Go to https://chatgpt.com
2. Click **Sign up**
3. Create an account using email, Google, Apple, or Microsoft
4. Complete the verification steps if prompted
5. Stop once you can sign in to ChatGPT in your browser

---

## ⚙️ Step 1 — Open Terminal

1. Press **Command (⌘) + Space**
2. Type: `Terminal`
3. Press Enter

You should see something like:

```
username@computer ~ %
```

---

## ⚙️ Step 2 — Check if Codex Is Already Installed

In Terminal, type:

```
codex --version
```

Press Enter

### ✅ If you see a version number
Example:
```
codex-cli 0.97.0
```

👉 Skip to Step 6

---

### ❌ If you see "command not found"
👉 Continue to Step 3

---

## ⚙️ Step 3 — Check if Node.js Is Installed

In Terminal, type:

```
node -v
```

Press Enter

Then type:

```
npm -v
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

### ❌ If you see "command not found"
👉 You need to install Node.js → go to Step 4

---

## ⚙️ Step 4 — Install Node.js

1. Go to:
   https://nodejs.org

2. Download the **LTS version**

3. Open the downloaded file

4. Follow all installation steps

---

### 🔁 After installing:
1. Close Terminal
2. Reopen Terminal
3. Run again:

```
node -v
npm -v
```

👉 Make sure both commands now show version numbers

---

## ⚙️ Step 5 — Install Codex CLI

In Terminal, run:

```
npm install -g @openai/codex
```

Wait for installation to complete

---

## ⚙️ Step 6 — Verify Codex Installation

Run:

```
codex --version
```

You should see a version number

---

### ❌ If you see "command not found"
- Close Terminal
- Reopen Terminal
- Try again

If it still does not work, the installation may not have completed successfully.

---

## ⚙️ Step 7 — Open Your Downloads Folder

In Terminal, type:

```
cd ~/Downloads
```

Press Enter

---

## ⚙️ Step 8 — Start Codex

Run:

```
codex
```

---

## ⚙️ Step 9 — Sign In

When prompted, choose:

👉 **Sign in with ChatGPT**

Follow the browser login steps

---

## ⚙️ Step 10 — Sandbox Setup

If prompted to choose a sandbox:

👉 Choose the **non-admin** option.

The exact wording may vary slightly.

---

## ⚙️ Step 11 — Continue to the Demo

Codex should now be running from your Downloads folder.

Continue to the demo instructions.

---

## ⚠️ Common Issues

### "node: command not found"
→ Node.js is not installed correctly

---

### "codex: command not found"
→ Install Codex first, then restart Terminal if needed

---

### Login problems
→ Make sure you completed browser login

---

### Install errors
→ If `npm install -g @openai/codex` fails, ask your instructor for help before continuing

---

## Next Step

[Continue to the Agent Demo](agent_demo.md)

[Back to AI Demo Overview](index.md)
