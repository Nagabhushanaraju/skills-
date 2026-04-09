# 🔀 What Is a Merge?

> The finish line — where your hard work officially becomes part of the main project.

---

## 🤔 The Problem Before Merging

You've been working on your branch. You added a new feature, committed your changes, and opened a pull request.

Your teammates reviewed everything. They love it. They approved it.

But your changes are still just sitting on your branch — they haven't actually been added to the main project yet.

**Merging is the final step that makes it official.**

---

## ✅ A Merge = Combining Two Branches Into One

When you merge, Git takes the changes from your branch and **adds them into the main branch**.

```
Before Merge:
main:   ────●────────────────●────►
                             ↑
your-branch:   ────●────●────╯
                  (work)   (merge here)

After Merge:
main:   ────●────────────────●────●────►
                             (your work is now here!)
```

---

## 🧩 What Happens During a Merge?

GitHub looks at two branches and figures out:

1. **What's the same?** — Keeps it as-is
2. **What did you add?** — Adds it to main
3. **What did you delete?** — Removes it from main
4. **Did two people edit the same spot?** → This is a **conflict** (see below)

---

## ⚠️ What Is a Merge Conflict?

A merge conflict happens when two branches changed the **exact same line** differently.

Example:
- Main branch says: `Color: blue`
- Your branch says: `Color: red`
- Someone else's branch says: `Color: green`

GitHub can't decide which one is correct — so it asks you to manually choose.

**Merge conflicts sound scary but they're common and easy to resolve once you've done it once.**

---

## 🟢 The Green Merge Button

On a pull request, there's a green button that says **"Merge pull request"**.

Before you see it, GitHub runs some automatic checks. When those pass, the button turns green — that's your signal that it's safe to merge.

![screenshot of green merge pull request button](/images/Green-merge-pull-request.png)

---

## 🗑️ After Merging — Delete Your Branch

Once your branch is merged, it's no longer needed. GitHub will show a **"Delete branch"** button — click it!

This keeps the repository clean. Your changes are safe in `main` now. The branch was just a temporary workspace.

---

## 🖱️ How to Merge (On GitHub — No Commands Needed)

1. Go to your Pull Request
2. Wait for any automatic checks to finish (the button turns green when ready)
3. Click **"Merge pull request"**
4. Click **"Confirm merge"**
5. Click **"Delete branch"**

Done! Your work is now officially part of the main project. 🎉

---

## 🔗 Learn More

- [GitHub Docs — Merging a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request)
- [Back to Glossary](../GLOSSARY.md)
- [Previous: What is a Pull Request?](./what-is-a-pull-request.md)
- [Go back to README](../README.md)
