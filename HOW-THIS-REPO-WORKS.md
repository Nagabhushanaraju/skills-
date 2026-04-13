# 🏗️ How This Repo Is Structured

> A map of every file and folder in this project, with a plain-English explanation of what each one does.
> Think of this as the "you are here" sign in a shopping mall.

---

## 📂 Top-Level Files

```
skills-/
│
├── README.md                  ← Start here! The main instructions page
├── GLOSSARY.md                ← Plain English definitions of all GitHub terms
├── HOW-THIS-REPO-WORKS.md    ← This file — a map of everything
├── CONTRIBUTING.md            ← How to try things out and contribute
├── LICENSE                    ← Legal stuff (MIT = free to use)
├── .gitignore                 ← Files that should NEVER be uploaded to GitHub
│
├── images/                    ← Screenshots used in the instructions
│
├── docs/                      ← Deep-dive beginner guides (one concept per file)
│   ├── what-is-git.md
│   ├── what-is-github.md
│   ├── what-is-a-branch.md
│   ├── what-is-a-commit.md
│   ├── what-is-a-pull-request.md
│   └── what-is-a-merge.md
│
└── .github/                   ← Hidden folder — GitHub reads this automatically
    ├── dependabot.yml          ← Tells GitHub to keep dependencies up to date
    ├── steps/                  ← The text shown at each step of the course
    │   ├── 0-welcome.md
    │   ├── 1-create-a-branch.md
    │   ├── 2-commit-a-file.md
    │   ├── 3-open-a-pull-request.md
    │   ├── 4-merge-your-pull-request.md
    │   └── X-finish.md
    └── workflows/              ← Automatic scripts that run when you do things
        ├── 0-welcome.yml
        ├── 1-create-a-branch.yml
        ├── 2-commit-a-file.yml
        ├── 3-open-a-pull-request.yml
        └── 4-merge-your-pull-request.yml
```

---

## 📁 Folder-by-Folder Breakdown

---

### 📄 `README.md` — The Front Door

This is the **first thing anyone sees** when they open this repository on GitHub.

It's written in **Markdown** — a simple formatting language where:
- `# Title` becomes a big heading
- `**bold**` becomes **bold**
- `[link text](url)` becomes a clickable link
- `-` at the start of a line becomes a bullet point

> 📖 Learn Markdown → [GitHub's Markdown guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

---

### 📄 `.gitignore` — The "Don't Upload This" List

Some files should **never** be uploaded to GitHub:
- System files (like `.DS_Store` on Mac)
- Files with passwords or secret keys
- Temporary files your computer creates automatically

The `.gitignore` file lists all of those. Git reads this file and automatically skips anything listed inside.

---

### 🖼️ `images/` — Screenshots for the Instructions

Every screenshot you see in the instructions (like "click here", "look for this button") is stored here as a `.png` file.

They're referenced in Markdown like this:
```markdown
![description of image](/images/filename.png)
```

---

### 📚 `docs/` — The Beginner's Learning Library

Each file in this folder explains **one concept** in plain English:

| File | What It Explains |
|------|-----------------|
| `what-is-git.md` | The version-tracking system underneath everything |
| `what-is-github.md` | The website that hosts your projects |
| `what-is-a-branch.md` | Your private workspace for changes |
| `what-is-a-commit.md` | Saving a snapshot of your work |
| `what-is-a-pull-request.md` | Proposing your changes for review |
| `what-is-a-merge.md` | Combining your changes into the main project |

> 👉 Go to → [docs/ folder](./docs/)

---

### ⚙️ `.github/workflows/` — The Automatic Behind-the-Scenes Scripts

These are **YAML files** — a type of configuration file that GitHub reads and executes automatically.

Each workflow file corresponds to one step in the learning course:

| File | When It Runs | What It Does |
|------|-------------|--------------|
| `0-welcome.yml` | When you push to `main` | Welcomes you and sets up Step 1 |
| `1-create-a-branch.yml` | When you create a branch | Checks if it's named correctly, moves to Step 2 |
| `2-commit-a-file.yml` | When you push a commit | Moves you to Step 3 |
| `3-open-a-pull-request.yml` | When you open a PR | Moves you to Step 4 |
| `4-merge-your-pull-request.yml` | When you merge | Shows the finish page |

> 💡 You don't need to edit these files. They just run automatically!
> 📖 Full YAML explanation → [docs/what-is-a-workflow.md](./docs/) _(coming soon)_

---

### 📋 `.github/steps/` — The Course Content

Each `.md` file here contains the **instructions shown on screen** for one step of the course.

When you complete a step, GitHub automatically swaps out the old step's content for the next step's content in the README.

| File | Content |
|------|---------|
| `0-welcome.md` | The initial welcome message |
| `1-create-a-branch.md` | Step 1 instructions |
| `2-commit-a-file.md` | Step 2 instructions |
| `3-open-a-pull-request.md` | Step 3 instructions |
| `4-merge-your-pull-request.md` | Step 4 instructions |
| `X-finish.md` | Congratulations message |
| `-step.txt` | A single number tracking which step you're on |

---

### 📄 `dependabot.yml` — Auto-Updater

This tells GitHub to automatically check if the tools used in the workflows are out of date and suggest updates. It runs once a month. You don't need to do anything with this file.

---

## 🔗 Where to Go Next

| I want to... | Go here |
|---|---|
| Understand key words | [GLOSSARY.md](./GLOSSARY.md) |
| Start the course | [README.md](./README.md) |
| Read about a specific concept | [docs/ folder](./docs/) |
| Try contributing | [CONTRIBUTING.md](./CONTRIBUTING.md) |
