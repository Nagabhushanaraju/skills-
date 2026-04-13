# 🌿 What Is a Branch?

> Your own private sandbox where you can break things, try things, and not worry about ruining the main project.

---

## 🤔 The Problem Without Branches

Imagine a Google Doc shared between 5 people.

All 5 people are editing it **at the same time, in the same document**.
- Someone accidentally deletes a paragraph.
- Two people change the same sentence differently.
- No one knows who did what.

Chaos. Right?

**Branches solve this problem.**

---

## ✅ A Branch = Your Own Private Copy

When you create a branch, you get a **personal copy** of the entire project to work on.

You can:
- Add files
- Delete files
- Edit anything

And **none of it affects the main project** until you're ready to share it.

---

## 🌳 The Branch Tree — Visualized

```
main branch (the "official" version):
────●─────────●──────────────────────●────►
   v1.0      v1.1                  v1.2

Your branch (your private copy):
                 ╰──●───────●───╮
                 added    fixed  (ready to merge back)
                 feature   bug
```

- You branch off from `main` at some point.
- You do your work independently.
- When done, you **merge** back into `main`.

---

## 🎯 Why Branches Matter

| Without Branches | With Branches |
|-----------------|--------------|
| One person works at a time | Everyone works at the same time |
| Mistakes break the main project | Mistakes only affect your branch |
| Hard to try experimental ideas | Safe to experiment freely |
| No record of who did what | Full history per branch |

---

## 📛 Naming Your Branch

Branch names are like file names — they should **describe what you're doing**:

| Good Branch Names | Bad Branch Names |
|------------------|-----------------|
| `add-login-page` | `branch1` |
| `fix-typo-in-readme` | `test` |
| `my-first-branch` | `abc` |
| `feature/user-profile` | `new` |

In this course, your branch must be named **exactly `my-first-branch`** because the automatic system is watching for that specific name.

---

## 🖱️ How to Create a Branch (On GitHub — No Commands Needed)

1. Go to the **`< > Code`** tab of the repository
2. Click the branch dropdown (it shows the current branch name, usually `main`)
3. Type a new branch name in the search box
4. Click **"Create branch: [your-name]"**

That's it! You're now on a new branch.

---

## 🔗 Learn More

- [GitHub Docs — About branches](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)
- [Back to Glossary](../GLOSSARY.md)
- [Next: What is a Commit?](./what-is-a-commit.md)
