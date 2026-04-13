# 📖 Glossary — Plain English Definitions

> Every weird word you'll hear on GitHub, explained like you're hearing it for the first time.
> No jargon. No assumptions. Just clear, honest explanations.

---

## 🔤 A–Z Glossary

---

### 🅱️ Branch

**In plain English:** A branch is your own private workspace.

Imagine you're painting on a canvas with a group of friends. Instead of everyone painting on the same canvas at the same time (chaos!), each person gets their own identical copy of the canvas to paint on. When someone finishes their piece, it gets combined (merged) into the main canvas.

A branch in GitHub works the same way.

- The main canvas = the `main` branch
- Your private copy = your new branch (e.g., `my-first-branch`)

> 📖 Full guide → [docs/what-is-a-branch.md](./docs/what-is-a-branch.md)

---

### 🅲 Commit

**In plain English:** A commit is a saved snapshot of your work at a specific moment.

Think of it like taking a photo of your work every time you make a meaningful change. If something goes wrong later, you can always look back at old photos and restore your work.

Each commit has:
- A **message** — a short description of what changed (e.g., "Added my name to the list")
- A **timestamp** — when the change was saved
- A **unique ID** — so GitHub can track it forever

> 📖 Full guide → [docs/what-is-a-commit.md](./docs/what-is-a-commit.md)

---

### 🅶 Git

**In plain English:** Git is the system that tracks all changes to your files automatically.

Think of Git as a very smart "undo history" — but instead of just remembering your last action, it remembers **every single change ever made**, by **every single person**, going all the way back to the very beginning.

Git runs on your computer (or GitHub's computers). It doesn't need the internet to work.

> 📖 Full guide → [docs/what-is-git.md](./docs/what-is-git.md)

---

### 🅷 GitHub

**In plain English:** GitHub is a website that hosts your Git projects online so others can see and work on them too.

If Git is the engine, GitHub is the car around it — it gives you a nice interface, lets you share your work, and lets multiple people collaborate from anywhere in the world.

> 📖 Full guide → [docs/what-is-github.md](./docs/what-is-github.md)

---

### 🅼 Merge

**In plain English:** Merging is combining two branches back together.

Going back to the canvas analogy: when you're done painting on your private copy, merging is the act of copying your changes onto the main shared canvas.

GitHub checks for any conflicts (two people editing the same spot) and helps you resolve them.

> 📖 Full guide → [docs/what-is-a-merge.md](./docs/what-is-a-merge.md)

---

### 🅿️ Pull Request (PR)

**In plain English:** A pull request is a formal way of saying "I'm done with my changes — can someone check them before we add them to the main project?"

It's like submitting an assignment for review before it gets officially accepted.

A pull request lets others:
- **See exactly what changed** (line by line)
- **Leave comments** or ask questions
- **Approve or request changes**
- **Merge** it when everyone's happy

> 📖 Full guide → [docs/what-is-a-pull-request.md](./docs/what-is-a-pull-request.md)

---

### 🆁 Repository (Repo)

**In plain English:** A repository is a project folder that lives on GitHub.

It holds all your files, plus the entire history of every change ever made to those files. Think of it as a Google Drive folder — but with superpowers:

- It remembers every version of every file, forever
- Multiple people can work on it at the same time
- Nothing is ever permanently lost

---

### 🆆 Workflow (GitHub Actions)

**In plain English:** A workflow is a set of automatic tasks that GitHub runs for you.

For example, every time you push code, GitHub can automatically run checks to make sure nothing is broken. In this repo, workflows are used to automatically advance you to the next lesson step.

You don't need to touch workflows to use this repo — they just run in the background.

> 📖 See the workflow files → [.github/workflows/](./.github/workflows/)

---

## 🔗 Want to Learn More?

| Topic | Link |
|-------|------|
| Full GitHub glossary | [docs.github.com/glossary](https://docs.github.com/get-started/quickstart/github-glossary) |
| GitHub beginner guide | [docs.github.com/get-started](https://docs.github.com/en/get-started) |
| Video: What is GitHub? | [YouTube](https://www.youtube.com/watch?v=pBy1zgt0XPc) |
| GitHub Skills courses | [skills.github.com](https://skills.github.com) |
