# Class Notes

Day-wise notes. Click a day in the index to jump there. Add a new `## Day N` heading when you teach the next topic, then add a row in the index.

---

## Index

| Day | Topic | Notes |
| --- | --- | --- |
| [Day 1](#day-1) | Tech overview | HTML, CSS, JS, React, Node, DB, Git, Cloud, Docker, CI/CD, DevTools |
| [Day 2](#day-2) | Git | Full lesson |
| [Day 3](#day-3) | *(add topic)* | |
| [Day 4](#day-4) | *(add topic)* | |

- [Day 1 — Tech overview](#day-1)
  - [HTML](#html)
  - [CSS](#css)
  - [JavaScript](#javascript)
  - [React and React Native](#react-and-react-native)
  - [Node.js](#nodejs)
  - [MongoDB](#mongodb)
  - [SQL](#sql)
  - [Git and GitHub](#git-and-github)
  - [AWS / Azure](#aws--azure)
  - [Docker](#docker)
  - [CI/CD Pipeline](#cicd-pipeline)
  - [Chrome DevTools](#chrome-devtools)
- [Day 2 — Git](#day-2)
  - [Core ideas](#core-ideas)
  - [Commands](#commands)
  - [Everyday workflow](#everyday-workflow)
  - [Cheat sheet](#cheat-sheet)
- [Day 3](#day-3)
- [Day 4](#day-4)

---

## Day 1

**Topic:** What is each technology?  
**Goal:** Students can name the stack pieces and say what each one is for. No deep commands today.

How a typical app fits together:

```text
Browser / Phone app
  HTML + CSS + JavaScript     →  what the user sees (web)
  React                       →  UI library for web
  React Native                →  UI library for iOS / Android
        ↓
  Node.js                     →  backend (server / API)
        ↓
  MongoDB  or  SQL            →  database
        ↓
  Git + GitHub                →  save and share code
  Docker                      →  run the app the same everywhere
  AWS / Azure                 →  host it in the cloud
  CI/CD                       →  test and deploy automatically
  Chrome DevTools             →  debug in the browser
```

### HTML

**HyperText Markup Language** — the structure of a web page (headings, paragraphs, images, forms, links).

It is not a programming language. It is tags that describe content.

```html
<h1>School Portal</h1>
<p>Welcome to class.</p>
<button>Login</button>
```

### CSS

**Cascading Style Sheets** — how the page looks (colors, fonts, layout, spacing).

HTML is the skeleton. CSS is the design.

```css
h1 {
  color: navy;
  font-size: 32px;
}
```

### JavaScript

The programming language of the browser. It makes pages **do things**: clicks, forms, API calls, showing/hiding content.

```javascript
document.querySelector("button").addEventListener("click", () => {
  alert("Logged in");
});
```

HTML = structure, CSS = style, JavaScript = behaviour.

### React and React Native

**React** — a JavaScript library for building web UIs from reusable **components**. Used for websites and web apps.

**React Native** — same idea (components, JavaScript), but it builds **mobile apps** (iOS and Android) instead of a website.

| | React | React Native |
| --- | --- | --- |
| Runs on | Browser | Phone |
| Output | Web page | Native mobile app |
| Language | JavaScript / TypeScript | JavaScript / TypeScript |

You do not need both on every project. Web → React. Mobile app → React Native.

### Node.js

JavaScript **on the server**, not in the browser.

Used to build APIs, backends, and tools (`npm`). The frontend talks to Node; Node talks to the database.

```text
React (UI)  →  request  →  Node.js API  →  database
```

### MongoDB

A **NoSQL** database. Data is stored as JSON-like documents, not tables.

Good when the shape of data changes often (flexible documents).

```text
{ "name": "Asha", "class": "10-A", "feesPaid": true }
```

### SQL

**Structured Query Language** — used with **relational** databases (MySQL, PostgreSQL, SQL Server). Data lives in **tables** with rows and columns, and tables can link to each other.

```sql
SELECT name, class FROM students WHERE class = '10-A';
```

| MongoDB | SQL |
| --- | --- |
| Documents | Tables |
| Flexible shape | Fixed columns |
| NoSQL | Relational |

Apps pick one (or both) depending on the data.

### Git and GitHub

**Git** — version control on your computer. Saves snapshots of code (commits), branches, history. (Full lesson is [Day 2](#day-2).)

**GitHub** — a website that hosts Git repos so a team can push, pull, review, and store the code in the cloud.

```text
Your laptop (Git)  ←→  GitHub (shared remote)
```

Git = the tool. GitHub = the remote hosting service (GitLab and Azure DevOps do the same job).

### AWS / Azure

**Cloud platforms.** Instead of running the app only on your laptop, you rent servers, databases, storage, and networking.

| | AWS | Azure |
| --- | --- | --- |
| Company | Amazon | Microsoft |
| Job | Host apps, DBs, files, etc. | Same idea |

You deploy the Node API, database, and sometimes the frontend here so students/users can open it on the internet.

### Docker

A way to **package** an app with its runtime so it runs the same on every machine.

“It works on my laptop” problems: Docker puts the app in a **container** (a lightweight, isolated box). Same container on your PC, a teammate’s PC, and the cloud.

### CI/CD Pipeline

**CI** = Continuous Integration — automatically build and test code when someone pushes to GitHub.

**CD** = Continuous Delivery / Deployment — automatically ship that code to a server (AWS/Azure) if tests pass.

```text
git push  →  tests run  →  build  →  deploy
```

Stops “it broke after I merged” from being a surprise. GitHub Actions is one common CI/CD tool.

### Chrome DevTools

Built into Google Chrome (`F12` or right-click → Inspect). Used to debug the **frontend**.

You can:

- see HTML/CSS (Elements)
- run JavaScript (Console)
- watch network requests (Network)
- check errors and performance

This is how you find why a button does nothing or an API call failed.

### Day 1 recap

| Tech | In one line |
| --- | --- |
| HTML | Page structure |
| CSS | Page look |
| JavaScript | Page behaviour |
| React | Web UI components |
| React Native | Mobile UI components |
| Node.js | JavaScript backend |
| MongoDB | Document database |
| SQL | Table database + query language |
| Git | Version control locally |
| GitHub | Shared Git hosting |
| AWS / Azure | Cloud hosting |
| Docker | Same app, same environment everywhere |
| CI/CD | Auto test and deploy |
| Chrome DevTools | Debug the browser |

[Back to index](#index)

---

## Day 2

**Topic:** Git  
**Goal:** Students can use a repo, stage and commit, branch, pull/push, merge, and undo local work.

Quick reference for Git: what it is, how a repo is structured, and the commands you will use every day.

### Core ideas

#### Repository

A **repository** (repo) is a project folder that Git is tracking. It contains:

- your working files
- a hidden `.git/` folder (the actual Git database: commits, branches, config)

Two common kinds:

| Type | Meaning |
| --- | --- |
| Local repo | On your machine (`git init` or `git clone`) |
| Remote repo | On GitHub / GitLab / Azure DevOps (the shared copy) |

#### Working tree

The **working tree** (or working directory) is the files you currently see and edit.

Git thinks in three places:

```text
Working tree     Staging area     Repository (commits)
(your files)  →  (git add)     →  (git commit)
```

| Area | What it holds |
| --- | --- |
| Working tree | Files you are editing right now |
| Staging area (index) | Files you have marked for the next commit |
| Repository | Saved snapshots (commits) in `.git/` |

#### Staging

**Staging** means choosing exactly what goes into the next commit.

- Change a file → it is **unstaged**
- `git add file` → it is **staged**
- `git commit` → staged changes become a commit

You can stage some files and leave others for later. That is the point of staging.

#### Commit

A **commit** is a snapshot of the project at one moment, plus:

- a message (why the change was made)
- author and date
- a unique hash (e.g. `a1b2c3d`)
- a pointer to the parent commit(s)

Commits form a **history**. Each commit points to the previous one, like a chain.

#### History

**History** is the list of commits on a branch.

Read it with `git log`. Each commit is one step. Branches, merges, and rebases change how that chain looks.

#### Tree

In Git internals, a **tree** is a snapshot of a directory: which files exist and which blob (file content) each one points to.

You do not use trees day to day. Think of them as: *a commit points to a tree, and that tree is the folder structure of that snapshot.*

#### `.gitignore`

A `.gitignore` file lists files and folders Git should **not** track.

Typical entries:

```gitignore
node_modules/
.env
dist/
*.log
.DS_Store
```

Rules:

- Put `.gitignore` at the repo root (you can also have nested ones)
- Already-tracked files are **not** ignored until you untrack them
- Commit `.gitignore` so the whole team ignores the same things

Do **not** commit secrets (`.env`, keys, credentials).

### Commands

#### `git init`

Turn the current folder into a new Git repo.

```bash
cd my-project
git init
```

Creates `.git/`. After this, `git add` and `git commit` work.

Use this for a **new** project. For an existing remote project, use `git clone` instead.

#### `git clone`

Copy a remote repo onto your machine (files + full history + remote named `origin`).

```bash
git clone https://github.com/user/repo.git
git clone https://github.com/user/repo.git my-folder-name
```

Then:

```bash
cd repo
```

You already have a local repo. You do **not** need `git init` after cloning.

#### `git add`

Stage files for the next commit.

```bash
git add file.txt              # one file
git add src/                  # a folder
git add .                     # everything in this folder (respects .gitignore)
git add -p                    # stage hunks interactively
```

`git add .` stages new files **and** changes. It does not unstage anything by itself.

#### `git commit`

Save the staged snapshot with a message.

```bash
git commit -m "Add student attendance filter"
```

Good messages:

- Focus on **why**, not only what
- Present tense: `Fix`, `Add`, `Update` (not `Fixed`, `Added`)
- Short first line (about 50–72 characters)

Examples:

```text
Add custom roles for school staff
Fix timetable clash when two teachers share a period
Update .gitignore to exclude local env files
```

Commit often, in small related chunks. One idea per commit is easier to review and revert.

#### `git branch` (and branch name formatting)

List, create, or delete branches.

```bash
git branch                    # list local branches (* = current)
git branch feature/roles-ui   # create a branch (does not switch)
git branch -d feature/roles-ui  # delete a merged branch
git branch -D feature/roles-ui  # force-delete (unmerged)
```

A **branch** is a movable pointer to a commit. `main` (or `master`) is usually the default.

##### Branch name formatting

Use lowercase, hyphens, and `/` for grouping. Avoid spaces and special characters.

| Pattern | Example | Use |
| --- | --- | --- |
| `feature/<short-name>` | `feature/custom-roles` | New functionality |
| `fix/<short-name>` | `fix/login-redirect` | Bug fix |
| `hotfix/<short-name>` | `hotfix/fee-rounding` | Urgent production fix |
| `chore/<short-name>` | `chore/gitignore` | Tooling, cleanup |
| `docs/<short-name>` | `docs/git-notes` | Documentation |

Rules:

- Lowercase only
- Words separated by `-` (kebab-case), not spaces or `_` mixed randomly
- No: `My Branch`, `Feature_Roles`, `feat/roles!!`
- Yes: `feature/custom-roles`, `fix/attendance-date`

#### `git checkout`

Switch branches, or restore files from another commit. Newer Git also has `git switch` (branches) and `git restore` (files).

```bash
git checkout main
git checkout -b feature/custom-roles   # create AND switch
git checkout -- file.txt               # discard local changes in that file
```

Safer modern equivalents:

```bash
git switch main
git switch -c feature/custom-roles
```

You cannot switch branches if you have conflicting uncommitted changes. Commit, stash, or discard them first.

#### `git pull`

Fetch remote commits **and** integrate them into your current branch.

```bash
git pull
git pull origin main
```

`git pull` = `git fetch` + `git merge` (or rebase, if configured).

Use this **before** you start work, and **before** you push, so your branch is up to date.

If someone else pushed to the same branch, pull first, then push.

#### `git push`

Upload your local commits to the remote.

```bash
git push
git push -u origin feature/custom-roles   # first push of a new branch
git push origin main
```

`-u` sets the upstream so later you can just run `git push` / `git pull`.

Push does **not** send uncommitted or unstaged work. Commit first.

#### `git restore` (not essential for daily flow)

Undo **uncommitted** changes in the working tree or staging area. It does not rewrite history.

```bash
git restore file.txt                 # discard working-tree changes
git restore --staged file.txt        # unstage, keep file contents
git restore --source=HEAD file.txt   # restore file from last commit
```

Older equivalent of unstaging: `git reset HEAD file.txt`.

Use restore when you want to throw away or unstage local edits. Use reset when you need to move a branch pointer (see below).

#### `git reset`

Move the current branch pointer. Can also change staging / working tree depending on mode.

| Mode | Command | Staging | Working files |
| --- | --- | --- | --- |
| Soft | `git reset --soft HEAD~1` | Keeps changes staged | Unchanged |
| Mixed (default) | `git reset HEAD~1` | Unstages changes | Files still modified |
| Hard | `git reset --hard HEAD~1` | Lost | Lost |

`HEAD~1` means “one commit before the current commit”.

Examples:

```bash
git reset HEAD file.txt          # unstage one file (keep edits)
git reset --soft HEAD~1          # undo last commit, keep everything staged
git reset --hard HEAD            # throw away all uncommitted changes
```

**Warning:** `git reset --hard` deletes uncommitted work. Do not reset commits that are already pushed unless the team agrees (rewrites shared history).

#### `git log`

Show commit history.

```bash
git log
git log --oneline
git log --oneline --graph --all
git log -5                       # last 5 commits
git log --author="Ram"
```

Useful one-liner:

```bash
git log --oneline --graph --decorate --all
```

Each line is a commit hash + message. The graph shows branches and merges.

#### `git status`

Show the current state of the working tree and staging area.

```bash
git status
git status -sb                   # short view
```

Tells you:

- which branch you are on
- whether you are ahead/behind the remote
- staged files
- unstaged modifications
- untracked files

Run this constantly. It is the safest way to know what Git will do next.

#### `git merge`

Combine another branch into your current branch. Creates a **merge commit** if histories diverged.

```bash
git checkout main
git pull
git merge feature/custom-roles
```

If both branches changed the same lines, Git stops with a **merge conflict**. You:

1. Open the conflicted files
2. Choose the correct code
3. `git add` the resolved files
4. `git commit` (completes the merge)

Merge **keeps history as it happened** (extra merge commit). Rebase rewrites it into a straight line.

#### `git rebase`

Replay your commits on top of another branch, as if you started from the latest point.

```bash
git checkout feature/custom-roles
git rebase main
```

Typical flow: update `main`, then rebase your feature onto it so the feature sits on top of latest `main`.

If there are conflicts: fix them, `git add`, then `git rebase --continue`. To abort: `git rebase --abort`.

**Do not rebase commits that are already pushed and shared**, unless the team uses force-push on purpose. Rebase rewrites hashes.

| | Merge | Rebase |
| --- | --- | --- |
| History | Preserves branch joins | Linear, rewritten |
| Extra commit | Yes (merge commit) | No |
| Shared branches | Safe | Risky if already pushed |

#### `git stash`

Temporarily shelf uncommitted changes so you can switch branches with a clean tree.

```bash
git stash                    # stash tracked changes
git stash -u                 # include untracked files
git stash push -m "wip roles page"
```

Stash is a stack. Latest stash is `stash@{0}`.

Use stash when you must switch context but are not ready to commit.

#### `git stash list`

Show all stashes.

```bash
git stash list
```

Example output:

```text
stash@{0}: On feature/custom-roles: wip roles page
stash@{1}: WIP on main: a1b2c3d Add login
```

#### `git stash apply`

Re-apply a stash **without** removing it from the list.

```bash
git stash apply                  # latest stash
git stash apply stash@{1}        # a specific stash
```

Related:

```bash
git stash pop                    # apply AND delete the stash
git stash drop stash@{0}         # delete without applying
git stash clear                  # delete all stashes
```

`apply` keeps the stash (safer). `pop` applies and removes it.

#### `git commit --amend -m "message"`

Replace the **latest commit** with a new one: same (or updated) staged changes, new message.

```bash
git commit --amend -m "Fix attendance date filter"
```

Use amend when you:

- just committed and the message is wrong
- forgot to stage a small file and have **not** pushed yet

```bash
git add forgotten-file.js
git commit --amend --no-edit     # keep the same message
```

**Do not amend a commit that is already pushed** unless you intend to force-push. Amend rewrites that commit’s hash, so the remote still has the old one.

### Everyday workflow

```text
git status
git pull
# ... edit files ...
git add .
git status
git commit -m "Add roles page to admin nav"
git push
```

Feature branch:

```bash
git switch main
git pull
git switch -c feature/custom-roles
# work, add, commit
git push -u origin feature/custom-roles
```

Catch up with main:

```bash
git switch main
git pull
git switch feature/custom-roles
git merge main          # or: git rebase main
```

### Cheat sheet

| Goal | Command |
| --- | --- |
| New local repo | `git init` |
| Copy a remote repo | `git clone <url>` |
| What changed? | `git status` |
| Stage files | `git add .` |
| Save snapshot | `git commit -m "message"` |
| Fix last commit (not pushed) | `git commit --amend -m "message"` |
| See history | `git log --oneline` |
| Create + switch branch | `git checkout -b feature/name` |
| Switch branch | `git checkout main` |
| Update from remote | `git pull` |
| Publish commits | `git push` |
| Combine branches | `git merge other-branch` |
| Replay onto another branch | `git rebase main` |
| Shelf work | `git stash` |
| List shelves | `git stash list` |
| Bring stash back | `git stash apply` |
| Discard file edits | `git restore file` |
| Undo last commit, keep files | `git reset --soft HEAD~1` |
| Ignore files | edit `.gitignore` |

[Back to index](#index)

---

## Day 3

*(Different topic — add this lesson later.)*

[Back to index](#index)

---

## Day 4

*(Different topic — add this lesson later.)*

[Back to index](#index)
