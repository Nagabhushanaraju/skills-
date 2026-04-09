# 📬 What Is a Pull Request?

> The professional way of saying "I made some changes — can someone review them before they go live?"

---

## 🤔 The Problem Without Pull Requests

Imagine you're working on a shared project with 10 people.

Everyone is making changes and pushing them **directly to the main project**.

No reviews. No checks. No chance to catch mistakes.

One person accidentally deletes a critical file. It goes live instantly. The project breaks.

**Pull requests prevent this.**

---

## ✅ A Pull Request (PR) = A Change Proposal + Review Process

A pull request is how you say:

> "I've been working on my branch. Here are the changes I made. Can everyone review them before they become official?"

It gives your team a chance to:
- **See exactly what changed** — line by line, highlighted in green (added) and red (removed)
- **Leave comments** — "This looks great!" or "Hmm, what if we did it this way instead?"
- **Request changes** — ask the author to fix something before approving
- **Approve** — give it the green light
- **Merge** — officially add the changes to the main project

---

## 🎭 The Pull Request Process — Step by Step

```
1. You work on your branch
        ↓
2. You're happy with your changes
        ↓
3. You open a Pull Request (PR)
        ↓
4. Teammates review your changes
        ↓
5. They approve (or ask for changes)
        ↓
6. Your branch gets merged into main ✅
        ↓
7. Your branch gets deleted (no longer needed)
```

---

## 👀 What Does a Pull Request Look Like?

When you open a PR, GitHub shows you:

| What You See | What It Means |
|-------------|---------------|
| 🟢 Green lines | Lines you **added** |
| 🔴 Red lines | Lines you **removed** |
| Conversation tab | Comments from reviewers |
| Files changed tab | Every file that was modified |
| Checks section | Automatic tests that run on your changes |

---

## 💡 Why "Pull" Request?

The name is a little confusing at first.

You're not pulling anything. You're pushing your changes and asking the main project to "pull them in."

The term comes from early Git workflows. Don't worry about it — just remember it means "please review and accept my changes."

---

## 🖱️ How to Open a Pull Request (On GitHub — No Commands Needed)

1. After committing to your branch, GitHub shows a yellow banner: **"Compare & pull request"** — click it!
2. If you miss that: go to the **Pull Requests** tab → click **New pull request**
3. Make sure:
   - **Base:** `main` (this is where your changes will go)
   - **Compare:** your branch (this is where your changes are now)
4. Write a title and description
5. Click **Create pull request**

That's it! Now others can review your work.

---

## 🔗 Learn More

- [GitHub Docs — About pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
- [Back to Glossary](../GLOSSARY.md)
- [Previous: What is a Commit?](./what-is-a-commit.md)
- [Next: What is a Merge?](./what-is-a-merge.md)
