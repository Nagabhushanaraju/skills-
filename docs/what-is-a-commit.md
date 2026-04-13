# 📸 What Is a Commit?

> Think of it as pressing "Save" — but a Save that remembers everything forever and tells a story.

---

## 🤔 The Problem Without Commits

You're working on a project. You save your file (like any normal person does).

A few days later, you realize you broke something that was working perfectly two days ago.

You press Ctrl+Z... but you've already closed and reopened the file 50 times since then. The undo history is gone.

**Your old working version is lost.**

A commit would have saved it.

---

## ✅ A Commit = A Named Snapshot of Your Entire Project

When you **commit** in Git/GitHub, you're saying:

> "Save a complete snapshot of all my files right now, and label it so I can find it later."

Unlike a regular "Save", a commit:
- **Never gets overwritten** — you can have thousands of commits and see all of them
- **Has a message** — you describe what changed ("Fixed typo in homepage")
- **Is permanent** — even months later, you can look back at any old commit

---

## 🎞️ Commits Create a Timeline

```
●──────────●──────────●──────────●──────────●
First      Added      Fixed      Added      Added dark
file       intro      typo       images     mode
(Oct 1)   (Oct 3)   (Oct 5)    (Oct 8)    (Oct 10)
```

You can jump to **any point** in this timeline whenever you want. Nothing is lost.

---

## 📝 Anatomy of a Commit

Every commit has three parts:

| Part | Example | What It Means |
|------|---------|---------------|
| **Message** | `"Add navigation menu"` | A short description of what changed |
| **Timestamp** | `Oct 10, 2024 at 3:42 PM` | When the commit was made |
| **ID (SHA)** | `a3f8c12` | A unique code to identify this exact commit |

The ID looks random, but it's like a fingerprint — **no two commits ever have the same one**.

---

## 💬 Writing Good Commit Messages

A commit message is a note for your future self (and your teammates).

| Bad Message | Good Message |
|-------------|-------------|
| `update` | `Fix broken link in footer` |
| `stuff` | `Add user login form` |
| `asdf` | `Remove unused CSS styles` |
| `changes` | `Update README with setup instructions` |

**Rule of thumb:** If you woke up 3 months from now and read just that message, would you know what the commit was about?

---

## 🖱️ How to Make a Commit (On GitHub — No Commands Needed)

1. Go to your branch on GitHub
2. Create or edit a file
3. Scroll down and find the **"Commit changes"** section
4. Write a short message in the text box
5. Click **"Commit changes"**

Done! Your snapshot is saved forever.

---

## 🔗 Learn More

- [GitHub Docs — About commits](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)
- [Back to Glossary](../GLOSSARY.md)
- [Previous: What is a Branch?](./what-is-a-branch.md)
- [Next: What is a Pull Request?](./what-is-a-pull-request.md)
