# Class Notes

Day-wise notes. Click a day in the index to jump there. Add a new `## Day N` heading when you teach the next topic, then add a row in the index.

---

## Index

| Day | Topic | Notes |
| --- | --- | --- |
| [Day 1](#day-1) | Tech overview | HTML, CSS, JS, React, Node, DB, Git, Cloud, Docker, CI/CD, DevTools |
| [Day 2](#day-2) | Git | Full lesson |
| [Day 3](#day-3) | HTML basics | Document structure, tags, text, lists, links, images |
| [Day 4](#day-4) | HTML layout and media | Semantic tags, div/span, tables, audio/video, paths |
| [Day 5](#day-5) | HTML forms | Inputs, labels, validation attributes, a11y, cheat sheet |
| [Day 6](#day-6) | CSS basics | Syntax, how to attach CSS, selectors, colors, fonts, cascade |
| [Day 7](#day-7) | CSS box model | Box model, display, spacing, backgrounds, positioning |
| [Day 8](#day-8) | CSS layout | Flexbox, grid, responsive, states, variables, cheat sheet |
| [Day 9](#day-9) | JS basics | Scripts, values, types, variables, operators, console |
| [Day 10](#day-10) | JS decisions and loops | Comparisons, if/else, loops, arrays as lists |
| [Day 11](#day-11) | JS functions and data | Functions, scope, objects, array methods |
| [Day 12](#day-12) | JS DOM | Select, change, create elements, click events |
| [Day 13](#day-13) | JS forms and storage | Submit, other events, localStorage, UI patterns |
| [Day 14](#day-14) | JS async and fetch | Promises, async/await, fetch, JSON, cheat sheet |

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
- [Day 3 — HTML basics](#day-3)
  - [What HTML is](#what-html-is)
  - [Tags, elements, attributes](#tags-elements-attributes)
  - [Page skeleton](#page-skeleton)
  - [Head: title and meta](#head-title-and-meta)
  - [Headings and text](#headings-and-text)
  - [Lists](#lists)
  - [Links](#links)
  - [Images](#images)
  - [Comments and common attributes](#comments-and-common-attributes)
  - [Block vs inline](#block-vs-inline)
  - [Day 3 recap](#day-3-recap)
- [Day 4 — HTML layout and media](#day-4)
  - [Semantic HTML](#semantic-html)
  - [div and span](#div-and-span)
  - [Tables](#tables)
  - [Media](#media)
  - [Code, quotes, and entities](#code-quotes-and-entities)
  - [File paths](#file-paths)
  - [Day 4 recap](#day-4-recap)
- [Day 5 — HTML forms](#day-5)
  - [Forms](#forms)
  - [Input types](#input-types)
  - [Labels, name, and value](#labels-name-and-value)
  - [Other form controls](#other-form-controls)
  - [Validation attributes](#validation-attributes)
  - [Accessibility](#accessibility)
  - [HTML5 extras](#html5-extras)
  - [How HTML connects to CSS and JS](#how-html-connects-to-css-and-js)
  - [Cheat sheet](#cheat-sheet-1)
  - [Day 5 recap](#day-5-recap)
- [Day 6 — CSS basics](#day-6)
  - [What CSS is](#what-css-is)
  - [How to add CSS](#how-to-add-css)
  - [Rules and syntax](#rules-and-syntax)
  - [Selectors](#selectors)
  - [Colors and fonts](#colors-and-fonts)
  - [Units](#units)
  - [Cascade, specificity, inheritance](#cascade-specificity-inheritance)
  - [Day 6 recap](#day-6-recap)
- [Day 7 — CSS box model](#day-7)
  - [The box model](#the-box-model)
  - [Display](#display)
  - [Backgrounds and borders](#backgrounds-and-borders)
  - [Spacing and sizing](#spacing-and-sizing)
  - [Positioning](#positioning)
  - [Day 7 recap](#day-7-recap)
- [Day 8 — CSS layout](#day-8)
  - [Flexbox](#flexbox)
  - [Grid](#grid)
  - [Responsive design](#responsive-design)
  - [Pseudo-classes and states](#pseudo-classes-and-states)
  - [Variables and transitions](#variables-and-transitions)
  - [How CSS connects to HTML and React](#how-css-connects-to-html-and-react)
  - [Cheat sheet](#cheat-sheet-2)
  - [Day 8 recap](#day-8-recap)
- [Day 9 — JS basics](#day-9)
  - [What JavaScript is](#what-javascript-is)
  - [How to add JavaScript](#how-to-add-javascript)
  - [Values and types](#values-and-types)
  - [Variables](#variables)
  - [Operators and strings](#operators-and-strings)
  - [Console and errors](#console-and-errors)
  - [Day 9 recap](#day-9-recap)
- [Day 10 — JS decisions and loops](#day-10)
  - [Comparisons and logic](#comparisons-and-logic)
  - [if and else](#if-and-else)
  - [Loops](#loops)
  - [Arrays as lists](#arrays-as-lists)
  - [Day 10 recap](#day-10-recap)
- [Day 11 — JS functions and data](#day-11)
  - [Functions](#functions)
  - [Scope](#scope)
  - [Objects](#objects)
  - [Array methods](#array-methods)
  - [Day 11 recap](#day-11-recap)
- [Day 12 — JS DOM](#day-12)
  - [The DOM](#the-dom)
  - [Selecting elements](#selecting-elements)
  - [Changing the page](#changing-the-page)
  - [Creating elements](#creating-elements)
  - [Click events](#click-events)
  - [Day 12 recap](#day-12-recap)
- [Day 13 — JS forms and storage](#day-13)
  - [Form events](#form-events)
  - [Other events](#other-events)
  - [localStorage](#localstorage)
  - [Small UI patterns](#small-ui-patterns)
  - [Day 13 recap](#day-13-recap)
- [Day 14 — JS async and fetch](#day-14)
  - [Sync vs async](#sync-vs-async)
  - [Promises and async/await](#promises-and-asyncawait)
  - [fetch and JSON](#fetch-and-json)
  - [How JS connects to React and Node](#how-js-connects-to-react-and-node)
  - [JS cheat sheet](#js-cheat-sheet)
  - [Day 14 recap](#day-14-recap)

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

It is not a programming language. It is tags that describe content. Full lessons are [Day 3](#day-3), [Day 4](#day-4), and [Day 5](#day-5).

```html
<h1>School Portal</h1>
<p>Welcome to class.</p>
<button>Login</button>
```

### CSS

**Cascading Style Sheets** — how the page looks (colors, fonts, layout, spacing).

HTML is the skeleton. CSS is the design. Full lessons are [Day 6](#day-6), [Day 7](#day-7), and [Day 8](#day-8).

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

**Recording:** [Day 2 class recording](https://recordingscodesagara.blob.core.windows.net/recordings/bt1/day%202.mp4)  
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

**Recording:** [Day 3 class recording](https://recordingscodesagara.blob.core.windows.net/recordings/bt1/day%203.mp4)  
**Topic:** HTML basics  
**Goal:** Students can write a complete HTML page with headings, text, lists, links, and images.

Quick reference for HTML: what it is, how a page is structured, and the tags you will use every day.

### What HTML is

**HTML** = HyperText Markup Language.

- **Markup** = tags that describe content (this is a heading, this is a paragraph, this is a link)
- **HyperText** = text that can link to other pages

HTML is **not** a programming language. There are no loops or if/else. The browser reads the tags and draws the page.

```text
HTML  →  structure (what is on the page)
CSS   →  look (colours, layout)
JS    →  behaviour (clicks, forms, APIs)
```

A browser always starts with an `.html` file. CSS and JavaScript are attached to it.

### Tags, elements, attributes

A **tag** is the name in angle brackets. An **element** is the opening tag + content + closing tag.

```html
<p>Welcome to class.</p>
```

| Piece | Example | Meaning |
| --- | --- | --- |
| Opening tag | `<p>` | Start of a paragraph |
| Content | `Welcome to class.` | What the user reads |
| Closing tag | `</p>` | End of the paragraph |
| Element | the whole line | One complete unit |

Some tags have **no content**. They are **empty** (void) tags. No closing tag.

```html
<img src="logo.png" alt="School logo">
<br>
<hr>
```

An **attribute** is extra information on the opening tag: `name="value"`.

```html
<a href="https://example.com" target="_blank">Open site</a>
<img src="photo.jpg" alt="Students in class">
```

Rules:

- Tag names are lowercase: `<h1>`, not `<H1>`
- Attribute values go in quotes
- Nest tags correctly: `<p><strong>Yes</strong></p>` — not `<p><strong>No</p></strong>`

### Page skeleton

Every HTML page uses the same outer shape.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>School Portal</title>
  </head>
  <body>
    <h1>School Portal</h1>
    <p>Welcome to class.</p>
  </body>
</html>
```

| Part | Job |
| --- | --- |
| `<!DOCTYPE html>` | Tells the browser this is HTML5 |
| `<html>` | Root of the whole page |
| `lang="en"` | Page language (helps screen readers and search) |
| `<head>` | Info for the browser — **not** shown as page content |
| `<body>` | What the user actually sees |

Save as `index.html`. Double-click it, or open it with Live Server. The browser shows only what is inside `<body>`.

### Head: title and meta

`<head>` does not paint the page. It configures it.

```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>School Portal — Home</title>
  <link rel="stylesheet" href="styles.css">
  <script src="app.js" defer></script>
</head>
```

| Tag | Job |
| --- | --- |
| `<title>` | Tab name (and Google search title) |
| `charset="UTF-8"` | Correct letters, including names like Ramū |
| `viewport` | Makes the page usable on phones |
| `<link>` | Attach a CSS file |
| `<script>` | Attach a JavaScript file (`defer` waits until HTML is parsed) |

Without charset, special characters can look broken. Without viewport, a phone shows a tiny desktop page.

### Headings and text

Headings are `h1` to `h6`. One **`h1` per page** — the main title. Then `h2` for sections, `h3` for subsections. Do not skip levels just to change size. CSS changes size; headings describe **outline**.

```html
<h1>School Portal</h1>
<h2>Notices</h2>
<h3>Exam timetable</h3>
<p>Mid-term exams start on 12 October.</p>
```

Text tags:

```html
<p>Normal paragraph.</p>
<p>This is <strong>important</strong> and this is <em>stressed</em>.</p>
<p>H<sub>2</sub>O and 2<sup>nd</sup> period.</p>
<br>          <!-- line break inside text — use sparingly -->
<hr>          <!-- horizontal rule: a divider -->
```

| Tag | Meaning | Use for |
| --- | --- | --- |
| `<p>` | Paragraph | Body text |
| `<strong>` | Strong importance | Warnings, key words (usually bold) |
| `<em>` | Emphasis | Stress a word (usually italic) |
| `<b>` / `<i>` | Bold / italic only | Look, not meaning — prefer `strong` / `em` |
| `<small>` | Side comment | Fine print |
| `<mark>` | Highlight | Search match, key phrase |
| `<br>` | Line break | A poem or an address — not for spacing between sections |
| `<hr>` | Thematic break | Divider between topics |

Prefer `<p>` + CSS margin over a stack of `<br>` tags.

### Lists

**Unordered** (`ul`) = bullets. **Ordered** (`ol`) = numbers.

```html
<h2>Subjects</h2>
<ul>
  <li>Maths</li>
  <li>Science</li>
  <li>English</li>
</ul>

<h2>Today's periods</h2>
<ol>
  <li>Assembly</li>
  <li>Maths</li>
  <li>Science</li>
</ol>
```

Nested list:

```html
<ul>
  <li>Class 10
    <ul>
      <li>10-A</li>
      <li>10-B</li>
    </ul>
  </li>
</ul>
```

**Description list** — term + definition (glossary, staff roles):

```html
<dl>
  <dt>Principal</dt>
  <dd>Heads the school.</dd>
  <dt>Class teacher</dt>
  <dd>Owns one section (for example 10-A).</dd>
</dl>
```

Rules:

- `li` only goes inside `ul` or `ol`
- `ul` / `ol` should contain `li` children, not bare text
- Use `ol` when order matters (steps, rank, timetable)

### Links

The `<a>` tag (anchor) creates a hyperlink. `href` is the destination.

```html
<a href="https://github.com">GitHub</a>
<a href="about.html">About the school</a>
<a href="#notices">Jump to notices</a>
<a href="mailto:office@school.edu">Email office</a>
<a href="tel:+911234567890">Call office</a>
<a href="https://example.com" target="_blank" rel="noopener noreferrer">
  Opens in a new tab
</a>
```

| `href` | Goes to |
| --- | --- |
| `https://...` | Another website (absolute URL) |
| `about.html` | Another file in this project (relative) |
| `#notices` | An element on this page with `id="notices"` |
| `mailto:` | Email app |
| `tel:` | Phone dialer (useful on mobile) |

`target="_blank"` opens a new tab. Always add `rel="noopener noreferrer"` with it (stops the new page from controlling yours).

The clickable text should describe the destination. Write `Exam timetable`, not `click here`.

### Images

```html
<img src="images/logo.png" alt="Greenwood High logo">
<img src="https://example.com/photo.jpg" alt="Students in the lab" width="400">
```

| Attribute | Job |
| --- | --- |
| `src` | Path or URL of the image file |
| `alt` | Text if the image fails, and for screen readers |
| `width` / `height` | Optional size in pixels (CSS is better for layout) |

Rules:

- `<img>` is empty — no closing tag
- **Always** write `alt`. If the image is only decoration, use `alt=""`
- Put files in a folder such as `images/`
- Formats you will use: `.png` (logo, transparency), `.jpg` (photos), `.svg` (icons), `.webp` (modern, smaller)

If `src` is wrong, the image is broken. Check the path (see [File paths](#file-paths) on Day 4).

### Comments and common attributes

```html
<!-- Staff-only note: replace this banner after exams -->
<p id="notices" class="alert" title="Updated this morning">
  Mid-term exams start on 12 October.
</p>
```

| Attribute | Job |
| --- | --- |
| `id` | Unique name on the page. One id per page. Used by links (`#notices`) and JavaScript |
| `class` | Reusable label for CSS. Many elements can share a class |
| `title` | Tooltip on hover (do not rely on it for important info) |

Comments (`<!-- ... -->`) are for humans. The browser ignores them. Do not put secrets in comments — anyone can View Source.

`id` vs `class`:

```text
id    →  one element   →  #notices in CSS
class →  many elements →  .alert in CSS
```

### Block vs inline

**Block** elements start on a new line and (by default) take the full width.

**Inline** elements sit inside a line of text.

| Block | Inline |
| --- | --- |
| `h1`–`h6`, `p`, `ul`, `ol`, `li`, `div`, `section` | `a`, `strong`, `em`, `span`, `img` |

```html
<p>Visit the <a href="library.html">library</a> after lunch.</p>
```

The link stays inside the sentence. A heading would jump to the next line.

You cannot put a block inside a `<p>` (invalid: `<p><div>...</div></p>`). You can put inline tags inside a `<p>`.

Day 4 covers `<div>` (generic block) and `<span>` (generic inline).

### Day 3 recap

| Tag | In one line |
| --- | --- |
| `<!DOCTYPE html>` | HTML5 document |
| `<html>` / `<head>` / `<body>` | Page shell |
| `<title>` | Browser tab name |
| `<h1>`–`<h6>` | Headings (outline) |
| `<p>` | Paragraph |
| `<strong>` / `<em>` | Importance / emphasis |
| `<ul>` `<ol>` `<li>` | Lists |
| `<a href="">` | Link |
| `<img src="" alt="">` | Image |
| `id` / `class` | Hooks for CSS and JS |

Practice: one `index.html` for a school homepage — title, heading, welcome paragraph, subject list, a link, and a logo.

[Back to index](#index)

---

## Day 4

**Recording:** [Day 4 class recording](https://recordingscodesagara.blob.core.windows.net/recordings/bt1/day%204.mp4)  
**Topic:** HTML layout and media  
**Goal:** Students can structure a page with semantic tags, build a table, and embed images, audio, video, and maps.

### Semantic HTML

**Semantic** tags name the *role* of a region. The browser, Google, and screen readers understand the page better than a pile of `<div>`s.

```html
<body>
  <header>
    <h1>School Portal</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="timetable.html">Timetable</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <main>
    <article>
      <h2>Sports day results</h2>
      <p>Class 10-A won the relay.</p>
    </article>

    <section>
      <h2>Notices</h2>
      <p>Fees due by Friday.</p>
    </section>

    <aside>
      <h2>Quick links</h2>
      <ul>
        <li><a href="calendar.html">Calendar</a></li>
      </ul>
    </aside>
  </main>

  <footer>
    <p>Greenwood High · office@school.edu</p>
  </footer>
</body>
```

| Tag | Meaning | Typical use |
| --- | --- | --- |
| `<header>` | Intro of the page or a section | Logo, site title |
| `<nav>` | Main navigation | Menu links |
| `<main>` | Unique page content | One per page |
| `<section>` | Themed group | Notices, features |
| `<article>` | Self-contained piece | News post, blog item |
| `<aside>` | Side content | Related links, tips |
| `<footer>` | End of page or section | Contact, copyright |

`article` vs `section`: if it could be syndicated on its own (a notice, a blog post), use `article`. If it is just a titled chunk of the page, use `section`.

Headings still matter inside these tags. A `section` should usually have a heading.

### div and span

When **no semantic tag fits**, use a generic box.

| Tag | Display | Use |
| --- | --- | --- |
| `<div>` | Block | Layout wrapper (card, row, column) — CSS will style it |
| `<span>` | Inline | Style a few words inside a sentence |

```html
<div class="card">
  <h2>Class 10-A</h2>
  <p>Class teacher: <span class="name">Asha Rao</span></p>
</div>
```

Rules:

- Do not wrap everything in `<div>` if `<header>`, `<main>`, or `<section>` is the real meaning
- Do not use `<div>` or `<span>` just to make text bold — use `<strong>` / CSS
- Later in React you will still see lots of `div`s. Semantics still apply on the real HTML that React outputs

### Tables

Use a table for **tabular data** (timetable, marks, fees). Do not use tables to lay out the whole page.

```html
<table>
  <caption>Class 10-A timetable</caption>
  <thead>
    <tr>
      <th>Period</th>
      <th>Subject</th>
      <th>Teacher</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Maths</td>
      <td>Rao</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Science</td>
      <td>Mehta</td>
    </tr>
  </tbody>
</table>
```

| Tag | Job |
| --- | --- |
| `<table>` | The table |
| `<caption>` | Title of the table (visible, and read by screen readers) |
| `<thead>` / `<tbody>` / `<tfoot>` | Header / body / footer rows |
| `<tr>` | One row |
| `<th>` | Header cell (column or row title) |
| `<td>` | Data cell |

Span cells:

```html
<td colspan="2">Assembly (all classes)</td>
<td rowspan="2">Sports</td>
```

- `colspan` = stretch across columns
- `rowspan` = stretch across rows

A table is rows of cells. Count cells so each row has the same width unless you intentionally span.

Styling (borders, zebra rows) is CSS. HTML only describes the data.

### Media

#### Figure

Group an image (or chart) with its caption.

```html
<figure>
  <img src="images/campus.jpg" alt="Main building from the gate">
  <figcaption>Greenwood High campus, 2026</figcaption>
</figure>
```

#### Audio and video

```html
<audio controls>
  <source src="audio/anthem.mp3" type="audio/mpeg">
  Your browser does not support audio.
</audio>

<video controls width="480" poster="images/sports-thumb.jpg">
  <source src="video/sports-day.mp4" type="video/mp4">
  Your browser does not support video.
</video>
```

| Attribute | Job |
| --- | --- |
| `controls` | Play / pause / volume UI |
| `autoplay` | Starts by itself — usually avoid (annoying, often blocked) |
| `muted` | Needed if you must autoplay |
| `loop` | Repeat |
| `poster` | Image shown before the video plays |

The text inside `<audio>` / `<video>` is a **fallback** for old browsers.

#### iframe (embed another page)

```html
<iframe
  src="https://www.google.com/maps/embed?pb=..."
  width="600"
  height="450"
  title="Map of Greenwood High"
  loading="lazy"
></iframe>
```

Used for maps, YouTube, and some widgets.

Rules:

- Always set `title` on an iframe (accessibility)
- `loading="lazy"` waits until the user scrolls near it
- You can only embed sites that **allow** it. Many sites block iframe
- Prefer a normal `<a>` link if an embed is not needed

### Code, quotes, and entities

```html
<p>Run <code>git status</code> before you commit.</p>

<pre><code>&lt;h1&gt;School Portal&lt;/h1&gt;
</code></pre>

<blockquote cite="https://example.com/handbook">
  Students must wear the uniform on weekdays.
</blockquote>
```

| Tag | Job |
| --- | --- |
| `<code>` | Short code in a sentence |
| `<pre>` | Keep spaces and line breaks (code blocks) |
| `<blockquote>` | A quotation from elsewhere |

**Entities** — characters that would break HTML if typed raw:

| You want | Write |
| --- | --- |
| `<` | `&lt;` |
| `>` | `&gt;` |
| `&` | `&amp;` |
| `"` | `&quot;` |
| non-breaking space | `&nbsp;` |

Inside a paragraph, `Tom &amp; Jerry` shows as `Tom & Jerry`. If you write a raw `&`, the HTML can break.

### File paths

`src` and `href` are paths. Wrong path = broken image or link.

```text
project/
  index.html
  about.html
  css/
    styles.css
  images/
    logo.png
  pages/
    fees.html
```

From `index.html`:

```html
<img src="images/logo.png" alt="Logo">
<a href="about.html">About</a>
<a href="pages/fees.html">Fees</a>
<link rel="stylesheet" href="css/styles.css">
```

From `pages/fees.html`:

```html
<img src="../images/logo.png" alt="Logo">
<a href="../index.html">Home</a>
```

| Path | Meaning |
| --- | --- |
| `images/logo.png` | Down into `images/` from this file |
| `../index.html` | Up one folder |
| `/images/logo.png` | From the **site root** (careful on local files) |
| `https://...` | Absolute URL on the internet |

`../` means parent folder. Count how many folders you must climb.

### Day 4 recap

| Tag | In one line |
| --- | --- |
| `<header>` `<nav>` `<main>` `<footer>` | Page landmarks |
| `<section>` `<article>` `<aside>` | Content regions |
| `<div>` / `<span>` | Generic block / inline |
| `<table>` `<tr>` `<th>` `<td>` | Tabular data |
| `<figure>` `<figcaption>` | Image + caption |
| `<audio>` `<video>` | Media with controls |
| `<iframe>` | Embed another page |
| `<code>` `<pre>` | Code |
| `&lt;` `&amp;` | Entities |

Practice: a `timetable.html` with header/nav/main/footer, a real table, one campus photo with caption, and a map iframe.

[Back to index](#index)

---

## Day 5

**Topic:** HTML forms  
**Goal:** Students can build a working form with labels, the right input types, and basic validation — ready to hook to JavaScript or a Node API later.

### Forms

A **form** collects user input and sends it somewhere.

```html
<form action="/register" method="post">
  <!-- controls go here -->
  <button type="submit">Register</button>
</form>
```

| Attribute | Job |
| --- | --- |
| `action` | URL that receives the data (your Node route later) |
| `method` | `get` (shows in the URL) or `post` (body, better for passwords and creates) |

For class demos with no backend yet, you can omit `action` or use `action="#"` and handle submit with JavaScript (`event.preventDefault()`).

`get` is fine for a search box. Use `post` for login, register, fees, anything private or that **changes** data.

### Input types

`<input>` is empty. The `type` changes the keyboard, the browser UI, and what is valid.

```html
<input type="text" name="fullName">
<input type="email" name="email">
<input type="password" name="password">
<input type="number" name="age" min="5" max="18">
<input type="date" name="dob">
<input type="file" name="photo" accept="image/*">
<input type="hidden" name="classId" value="10A">
```

| `type` | What the user gets |
| --- | --- |
| `text` | Normal line of text (default) |
| `email` | Email keyboard; browser checks for `@` |
| `password` | Hidden characters |
| `number` | Numeric stepper |
| `tel` | Phone keyboard |
| `url` | Expects a web address |
| `search` | Search field (often has a clear ×) |
| `date` / `time` / `datetime-local` | Date / time picker |
| `file` | File picker |
| `hidden` | Not shown; still submitted |
| `checkbox` | On/off |
| `radio` | Pick one of a group |
| `submit` / `reset` / `button` | Buttons (prefer `<button>` instead) |

Pick the type that matches the data. `email` and `date` give you free validation and a better mobile keyboard.

### Labels, name, and value

Every visible control needs a **label**. Clicking the label focuses the input.

```html
<label for="email">Email</label>
<input id="email" name="email" type="email">
```

`for` on the label must match `id` on the input.

Or wrap the control (no `for` needed):

```html
<label>
  Email
  <input name="email" type="email">
</label>
```

**`name`** is what the server (and `FormData`) uses as the field key. Without `name`, that value is **not** submitted.

**`value`** is the current data. For text inputs it is what the user typed. For radio/checkbox it is the value sent when selected.

```text
label  →  human-readable (on screen)
id     →  hook up label + CSS + JS
name   →  key sent to the backend
value  →  data sent (or default shown)
```

### Other form controls

```html
<label for="about">About the student</label>
<textarea id="about" name="about" rows="4" cols="40"></textarea>

<label for="section">Section</label>
<select id="section" name="section">
  <option value="">Choose section</option>
  <option value="10A">10-A</option>
  <option value="10B">10-B</option>
</select>

<fieldset>
  <legend>Bus required?</legend>
  <label><input type="radio" name="bus" value="yes"> Yes</label>
  <label><input type="radio" name="bus" value="no"> No</label>
</fieldset>

<label>
  <input type="checkbox" name="terms" value="accepted" required>
  I agree to the school rules
</label>

<button type="submit">Save</button>
<button type="reset">Clear</button>
<button type="button">Preview</button>
```

| Control | Job |
| --- | --- |
| `<textarea>` | Multi-line text |
| `<select>` + `<option>` | Dropdown |
| `radio` | One choice; **same `name`** groups them |
| `checkbox` | Independent yes/no (or several with the same `name`) |
| `<fieldset>` + `<legend>` | Group related controls (radios, address) |
| `<button type="submit">` | Send the form |
| `<button type="button">` | JS only — does **not** submit |
| `<button type="reset">` | Clears fields — use rarely |

A `<button>` inside a form defaults to `submit`. If a button should only run JavaScript, set `type="button"`.

### Validation attributes

The browser can block submit before any JavaScript runs.

```html
<input
  type="email"
  name="email"
  required
  placeholder="asha@school.edu"
  maxlength="80"
  autocomplete="email"
>
<input type="number" name="marks" min="0" max="100" step="1">
<input type="text" name="roll" pattern="[0-9]{3}" title="3-digit roll number">
```

| Attribute | Job |
| --- | --- |
| `required` | Must be filled |
| `placeholder` | Hint inside the box (not a label — still need `<label>`) |
| `min` / `max` | Number or date range |
| `minlength` / `maxlength` | Text length |
| `step` | Allowed increments (`0.01` for money) |
| `pattern` | Regex the value must match |
| `disabled` | Greyed out; **not** submitted |
| `readonly` | Visible, not editable; **is** submitted |
| `autocomplete` | Helps the browser fill name, email, etc. |

HTML validation is a first filter. The **server** (Node) must validate again. Anyone can bypass the browser.

`placeholder` disappears when the user types. Never use it as the only label.

### Accessibility

Accessible HTML helps screen-reader users, keyboard users, and SEO. Most of it is tags you already have, used correctly.

| Do | Why |
| --- | --- |
| `lang` on `<html>` | Correct pronunciation |
| One `h1`, then `h2`… in order | Page outline |
| `alt` on images | Image is described if it cannot be seen |
| `<label>` on every control | Name is announced with the field |
| `title` on `<iframe>` | Embedded frame has a name |
| Visible focus (CSS later) | Keyboard users see where they are |
| Buttons that say the action | `Save student`, not `OK` |

Landmarks from Day 4 (`header`, `nav`, `main`, `footer`) let someone jump by region instead of tabbing through everything.

Skip these and the page still *looks* fine. It will fail real users and many audits.

### HTML5 extras

Useful tags you will see in modern pages:

```html
<time datetime="2026-10-12">12 October 2026</time>

<address>
  Greenwood High<br>
  office@school.edu
</address>

<details>
  <summary>Fee rules</summary>
  <p>Pay by the 5th of each month. Late fee is ₹50.</p>
</details>
```

| Tag | Job |
| --- | --- |
| `<time datetime="">` | Machine-readable date (good for schedules) |
| `<address>` | Contact for the page or article (not any postal address on earth) |
| `<details>` / `<summary>` | Expand/collapse without JavaScript |

### How HTML connects to CSS and JS

```html
<!-- in <head> -->
<link rel="stylesheet" href="css/styles.css">
<script src="js/app.js" defer></script>
```

```css
/* styles.css — select by element, class, or id */
h1 { color: navy; }
.alert { background: #fff3cd; }
#notices { border-left: 4px solid gold; }
```

```javascript
// app.js — select, then listen
document.querySelector("form").addEventListener("submit", (event) => {
  event.preventDefault();
  const data = new FormData(event.target);
  console.log(data.get("email"));
});
```

Later:

- **React** still produces HTML. The same tags and accessibility rules apply
- **Node** receives `name`/`value` pairs from the form (or JSON from JavaScript)

If the HTML structure is messy, CSS and JS become messy. Clean tags first. CSS in depth is [Day 6](#day-6), [Day 7](#day-7), and [Day 8](#day-8).

### Cheat sheet

| Goal | HTML |
| --- | --- |
| Page shell | `<!DOCTYPE html>` + `html` / `head` / `body` |
| Tab title | `<title>` |
| Heading | `<h1>` … `<h6>` |
| Paragraph | `<p>` |
| Bullet list | `<ul><li>…</li></ul>` |
| Numbered list | `<ol><li>…</li></ol>` |
| Link | `<a href="url">text</a>` |
| Image | `<img src="" alt="">` |
| Unique hook | `id="notices"` |
| CSS hook | `class="card"` |
| Page layout | `header` `nav` `main` `section` `article` `aside` `footer` |
| Generic box | `<div>` / `<span>` |
| Table | `table` `tr` `th` `td` |
| Form | `<form method="post">` |
| Labelled field | `<label for="id">` + `<input id="id" name="">` |
| Dropdown | `<select>` + `<option>` |
| Long text | `<textarea>` |
| One of many | `input type="radio"` same `name` |
| Yes/no | `input type="checkbox"` |
| Submit | `<button type="submit">` |
| Required field | `required` |
| Comment | `<!-- ... -->` |
| Less-than sign | `&lt;` |

### Day 5 recap

A form is labelled controls with `name`s, wrapped in `<form>`, submitted with a button.

Browser checks (`required`, `type="email"`) help users. The API still must validate.

HTML across Days 3–5 is the **structure** of every web screen you will build in this course — including React screens, which compile down to these same tags.

Practice: a `register.html` student form — name, email, password, section dropdown, bus radio, terms checkbox, submit. Open it in Chrome, Inspect the elements, submit and watch the Network tab (or a `console.log` of `FormData`).

[Back to index](#index)

---

## Day 6

**Recording:** [Day 6 class recording](https://recordingscodesagara.blob.core.windows.net/recordings/bt1/day%206.mp4)  
**Topic:** CSS basics  
**Goal:** Students can attach a stylesheet, write selectors, and style text and colors — and explain why one rule wins over another.

Quick reference for CSS: what it is, how it connects to HTML, and the rules you will write every day.

### What CSS is

**CSS** = Cascading Style Sheets.

HTML says *what* is on the page. CSS says *how it looks*.

```text
HTML  →  structure (heading, form, table)
CSS   →  look (navy heading, padded card, two columns)
JS    →  behaviour (clicks, submit, APIs)
```

CSS cannot add a heading that is not in the HTML. It can only style elements that already exist (or generate tiny extras with `::before` / `::after` on Day 8).

A **stylesheet** is a list of rules. The browser applies them when it paints the page.

### How to add CSS

Three ways. Use **external** CSS for real projects.

```html
<!-- 1. External (best) — in <head> -->
<link rel="stylesheet" href="css/styles.css">

<!-- 2. Internal — in <head>, one page only -->
<style>
  h1 { color: navy; }
</style>
```

```html
<!-- 3. Inline — on one element. Avoid for real layouts. -->
<h1 style="color: navy;">School Portal</h1>
```

| Method | Where | Use |
| --- | --- | --- |
| External | `.css` file + `<link>` | Whole site. One file, many pages |
| Internal | `<style>` in `<head>` | Quick demo on a single HTML file |
| Inline | `style=""` on a tag | Tiny one-off override — not for a whole page |

Same folder idea as HTML [file paths](#file-paths):

```text
project/
  index.html
  css/
    styles.css
```

From `index.html`: `href="css/styles.css"`.

Put `<link>` in `<head>` so styles load before the body paints. You can add more than one stylesheet; later files can override earlier ones (see cascade below).

### Rules and syntax

```css
/* selector { property: value; } */
h1 {
  color: navy;
  font-size: 32px;
}
```

| Piece | Example | Meaning |
| --- | --- | --- |
| Selector | `h1` | Which elements |
| Declaration | `color: navy;` | One style |
| Property | `color` | What to change |
| Value | `navy` | The setting |
| Block | `{ ... }` | All declarations for that selector |

Rules:

- End each declaration with `;`
- Quotes around font names with spaces: `"Segoe UI"`
- Comments are `/* like this */` — not `<!-- -->`
- CSS is not HTML. Do not put tags inside the `.css` file

Invalid CSS is ignored. One broken line does not always kill the whole file, but a missing `}` can.

### Selectors

Selectors pick HTML. Match them to `class` and `id` from [Day 3](#comments-and-common-attributes).

```html
<h1>School Portal</h1>
<p class="alert" id="notices">Fees due Friday.</p>
<p class="alert muted">Optional notice.</p>
```

```css
h1 { }                 /* all <h1> elements */
.alert { }             /* class="alert" */
#notices { }           /* id="notices" — one per page */
.alert.muted { }       /* both classes on the same element */
p.alert { }            /* <p> that also has class alert */

header nav a { }       /* descendant: <a> anywhere inside header nav */
header > h1 { }        /* child: <h1> directly inside <header> */
h1, h2, h3 { }         /* grouping: same styles on several selectors */
```

| Selector | Matches | CSS prefix |
| --- | --- | --- |
| Element | Every tag of that name | `p` |
| Class | Every element with that class | `.alert` |
| ID | The one element with that id | `#notices` |
| Group | All listed selectors | `h1, h2` |
| Descendant | Nested anywhere inside | `nav a` |
| Child | One level down only | `nav > a` |

Prefer **classes** for styling. Use **ids** for unique page hooks (skip links, JavaScript). Do not style by long HTML paths (`body div div p span`) — a class is clearer and survives layout changes.

### Colors and fonts

```css
h1 {
  color: navy;                 /* text */
  background-color: #f4f7fb;   /* behind the text */
  font-family: "Segoe UI", system-ui, sans-serif;
  font-size: 2rem;
  font-weight: 700;
  line-height: 1.3;
  text-align: center;
  text-decoration: none;
  letter-spacing: 0.02em;
}
```

Colors you will use:

| Form | Example | Notes |
| --- | --- | --- |
| Name | `navy`, `white` | Fine for teaching; limited set |
| Hex | `#1e3a5f` | Most common in real CSS |
| RGB | `rgb(30, 58, 95)` | Same idea as hex |
| RGBA | `rgba(0, 0, 0, 0.4)` | Last number is opacity 0–1 |

Fonts:

- `font-family` is a **stack**: first available font wins, then the next
- Always end with a generic: `sans-serif`, `serif`, or `monospace`
- `font-size` for size, `font-weight` for bold (`400` normal, `700` bold)
- `line-height` around `1.5` for body text — easier to read
- `text-align`: `left` \| `center` \| `right` \| `justify`
- Links default to underline and blue. Style `a` and `a:hover` together (hover is Day 8)

Load a web font later with Google Fonts or `@font-face`. For class, system fonts are enough.

### Units

| Unit | Meaning | Typical use |
| --- | --- | --- |
| `px` | Pixels | Borders, small tweaks |
| `%` | Percent of the **parent** | Widths: `width: 50%` |
| `em` | Relative to **this element's** font-size | Padding that scales with text |
| `rem` | Relative to the **root** (`html`) font-size | Font sizes, spacing on a whole site |
| `vh` / `vw` | 1% of the viewport height / width | Full-screen hero: `min-height: 100vh` |

```css
html { font-size: 16px; }   /* 1rem = 16px unless the user zooms */

h1 { font-size: 2rem; }     /* 32px at default root */
p  { font-size: 1rem; }
.card { width: 90%; max-width: 40rem; }
```

Prefer `rem` for type and spacing so the page scales if the user changes browser font size. Use `%` or `max-width` so layouts do not overflow on phones. `px` is fine for a 1px border.

### Cascade, specificity, inheritance

**Cascade** = when several rules match, the browser picks a winner.

Order of power (low → high):

1. Browser default styles
2. Your stylesheet (later rule beats earlier rule **if** specificity is equal)
3. Inline `style=""`
4. `!important` (avoid — it fights you later)

**Specificity** (who is more precise):

```text
element     <  class / pseudo-class  <  id  <  inline style
  p                .alert                 #notices
```

```css
p { color: black; }           /* loses */
.alert { color: #7a5b00; }    /* wins over p */
#notices { color: #5c3d00; }  /* wins over .alert */
```

Tied specificity → the **last** rule in the file wins.

**Inheritance:** some properties pass to children (`color`, `font-family`, `line-height`). Box properties do **not** (`margin`, `padding`, `border`, `width`).

```css
body {
  font-family: system-ui, sans-serif;  /* children inherit this */
  color: #222;
}
```

That is why you set fonts on `body` once, not on every tag.

Inspect in Chrome: right-click → Inspect → **Styles**. Crossed-out declarations lost the cascade. Use this when “my CSS is not working”.

### Day 6 recap

| Idea | In one line |
| --- | --- |
| External CSS | `<link rel="stylesheet" href="css/styles.css">` |
| Rule | `selector { property: value; }` |
| Class / id | `.alert` / `#notices` |
| Group | `h1, h2 { }` |
| Descendant | `nav a` |
| `rem` | Size relative to root font |
| Specificity | element < class < id |
| Inherit | fonts and color; not margin/padding |

Practice: `index.html` + `css/styles.css`. Style the school homepage heading, body font, a `.alert` notice, and nav links. Change one rule and watch it update. If nothing changes, check the path and the Styles panel.

[Back to index](#index)

---

## Day 7

**Recording:** [Day 7 class recording](https://recordingscodesagara.blob.core.windows.net/recordings/bt1/day%207.mp4)  
**Topic:** CSS box model  
**Goal:** Students can size and space elements with padding, border, and margin, control `display`, and place a header or badge with positioning.

### The box model

Every element is a **box**:

```text
margin        (outside, transparent — pushes neighbours away)
  border
    padding   (inside, around the content)
      content (text, image, or child boxes)
```

```css
.card {
  box-sizing: border-box;   /* width includes padding + border */
  width: 320px;
  padding: 16px;
  border: 1px solid #d0d7de;
  margin: 16px auto;        /* top/bottom 16px; left/right centered */
}
```

| Part | What it does |
| --- | --- |
| `content` | The text or children |
| `padding` | Space inside the border |
| `border` | Line around the padding |
| `margin` | Space outside the border |

**`box-sizing: border-box`** — put this on everything at the start of the file. Then `width: 320px` is the visible width, not “content plus mystery padding”.

```css
*,
*::before,
*::after {
  box-sizing: border-box;
}
```

Shorthand order is **top, right, bottom, left** (clock):

```css
margin: 8px 16px 24px 32px;
padding: 12px;          /* all four sides */
padding: 12px 20px;     /* top/bottom | left/right */
```

**Margin collapse:** vertical margins of siblings can combine into one (the larger one). Padding does not collapse. If two cards stick together oddly, inspect margin — that is often why.

`margin: auto` on left and right centers a **block** that has a width.

### Display

`display` changes how the box participates in layout.

| Value | Behaviour |
| --- | --- |
| `block` | New line, full width (`h1`, `p`, `div`) |
| `inline` | Sits in the text (`a`, `strong`, `span`). **width / height / vertical margin ignored** |
| `inline-block` | Sits in a line, but width/height/padding work |
| `none` | Removed from layout (not visible, no gap) |
| `flex` | Children laid out on an axis (Day 8) |
| `grid` | Children on rows and columns (Day 8) |

```css
.badge { display: inline-block; padding: 4px 8px; }
.hidden { display: none; }
nav a { display: inline-block; padding: 8px 12px; }
```

`visibility: hidden` hides the element but **keeps the gap**. `display: none` removes it.

This is the same block vs inline idea from [Day 3](#block-vs-inline), now under your control.

### Backgrounds and borders

```css
.hero {
  background-color: #1e3a5f;
  background-image: url("../images/campus.jpg");
  background-size: cover;
  background-position: center;
  color: white;
}

.card {
  border: 1px solid #d0d7de;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
}

img {
  max-width: 100%;
  height: auto;
  display: block;       /* removes the extra gap under images */
}
```

| Property | Job |
| --- | --- |
| `background-color` | Fill |
| `background-image` | Photo or pattern (`url(...)`) |
| `background-size` | `cover` fills the box (may crop); `contain` shows all |
| `border` | `width style color` — styles: `solid` `dashed` `none` |
| `border-radius` | Rounded corners (`50%` on a square → circle) |
| `box-shadow` | Soft depth. Do not fake a whole layout with shadows |

`max-width: 100%` on images stops them bursting out of the card.

### Spacing and sizing

```css
.wrap {
  width: 90%;
  max-width: 960px;
  min-height: 100vh;
  margin: 0 auto;
  padding: 24px 16px;
}

.notice {
  overflow: auto;        /* scroll if content is taller than the box */
}
```

| Property | Job |
| --- | --- |
| `width` / `height` | Size of the box (with `border-box`, this is the visible size) |
| `max-width` | Cap on large screens (`960px` is a common reading width) |
| `min-height` | At least this tall (footer at the bottom of a short page) |
| `overflow` | `visible` (default), `hidden` (clip), `auto` (scroll if needed) |

Do not set a fixed `height` on text containers unless you must — text will overflow when the student translates the page or zooms.

Space **between** cards with `margin` or, better on Day 8, `gap` on a flex/grid parent. Space **inside** a card with `padding`.

Style lists and links while you are here:

```css
ul { list-style: disc; padding-left: 1.25rem; }
a { color: #1e3a5f; text-decoration: none; }
a:focus { outline: 2px solid gold; outline-offset: 2px; }
```

Keep a visible **focus** outline for keyboard users ([Day 5 accessibility](#accessibility)).

### Positioning

`position` changes how the box is placed relative to the normal flow.

| Value | Meaning |
| --- | --- |
| `static` | Default. `top` / `left` do nothing |
| `relative` | Stay in flow; `top`/`left` nudge it. Also becomes the **anchor** for absolute children |
| `absolute` | Out of flow. Placed against the nearest positioned ancestor (or the page) |
| `fixed` | Out of flow. Stuck to the **viewport** (always-on nav) |
| `sticky` | In flow until you scroll past `top`, then it sticks |

```css
header {
  position: sticky;
  top: 0;
  z-index: 10;
  background: white;
}

.card {
  position: relative;
}

.card .badge {
  position: absolute;
  top: 8px;
  right: 8px;
}
```

`top` `right` `bottom` `left` only work when `position` is not `static`.

**`z-index`** stacks overlapping boxes. Higher number is on top. It only applies to positioned elements (and flex/grid items). Use small numbers (`1`, `10`, `100`) — not `999999`.

Normal page layout should still be **flow** (block, flex, grid). Positioning is for badges, sticky headers, and overlays — not for building the whole timetable.

### Day 7 recap

| Idea | In one line |
| --- | --- |
| Box | content + padding + border + margin |
| `border-box` | Width includes padding and border |
| `display: none` | Hide and remove from layout |
| `padding` vs `margin` | Inside vs outside the border |
| `max-width` + `margin: 0 auto` | Centered page column |
| `position: relative` | Anchor for `absolute` children |
| `sticky` | Header that follows you down the page |
| `z-index` | Who sits on top |

Practice: turn the school homepage into cards — padding, border, radius, shadow. Center a `.wrap` at `max-width: 960px`. Put a sticky header and an “New” badge on one notice.

[Back to index](#index)

---

## Day 8

**Topic:** CSS layout  
**Goal:** Students can build a nav and a two-column page with flexbox, a simple grid, a mobile breakpoint, and hover/focus states.

### Flexbox

Set `display: flex` on a **parent**. Children become flex items on one axis.

```css
.row {
  display: flex;
  flex-wrap: wrap;
  gap: 16px;
  justify-content: space-between; /* main axis */
  align-items: center;            /* cross axis */
}

.row .grow { flex: 1; }           /* take leftover space */
```

Default **main axis** is horizontal (`flex-direction: row`). Column is vertical:

```css
.stack {
  display: flex;
  flex-direction: column;
  gap: 12px;
}

nav {
  display: flex;
  gap: 8px;
  align-items: center;
}
```

| Property (on parent) | Job |
| --- | --- |
| `flex-direction` | `row` (default) or `column` |
| `justify-content` | Along the main axis: `flex-start` `center` `space-between` `space-around` |
| `align-items` | On the cross axis: `stretch` (default) `center` `flex-start` |
| `flex-wrap` | `nowrap` (default) or `wrap` so items drop to the next line |
| `gap` | Space **between** items (better than margin on each child) |

| Property (on child) | Job |
| --- | --- |
| `flex: 1` | Grow to fill leftover space |
| `flex: 0 0 200px` | Do not grow/shrink; stay 200px |
| `align-self` | Override `align-items` for one item |

Mental model:

```text
justify-content  →  along the row (or column, if direction is column)
align-items      →  the other way (cross axis)
```

Use flex for nav bars, toolbars, a sidebar + content row, and lists of cards that wrap.

### Grid

Grid is rows **and** columns at once. Stronger than flex when you need a 2D page (dashboard, photo gallery, form layout).

```css
.layout {
  display: grid;
  grid-template-columns: 240px 1fr;  /* sidebar | fluid main */
  gap: 24px;
}

.cards {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 16px;
}
```

| Property | Job |
| --- | --- |
| `grid-template-columns` | Column tracks. `1fr` = one share of leftover space |
| `grid-template-rows` | Row tracks (often skip this and let content define height) |
| `gap` | Space between tracks |
| `repeat(3, 1fr)` | Three equal columns |
| `minmax(0, 1fr)` | Equal columns that can shrink (avoids overflow) |

Place one item:

```css
.layout header { grid-column: 1 / -1; }  /* span all columns */
```

Start with **flex** for one-dimensional UI (nav, a row of buttons). Use **grid** when you can sketch the page as boxes on graph paper.

A common page:

```text
header  (full width)
nav     |  main
        |  aside
footer  (full width)
```

That is a grid. The nav inside the header can still be flex.

### Responsive design

**Responsive** = the same HTML, different CSS at different widths. Phones do not get a second website.

The viewport meta from [Day 3](#head-title-and-meta) is required or media queries will not match real phone widths.

```css
.cards {
  display: grid;
  grid-template-columns: 1fr;
  gap: 16px;
}

@media (min-width: 700px) {
  .cards {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (min-width: 1000px) {
  .cards {
    grid-template-columns: repeat(3, 1fr);
  }
}
```

| Idea | Practice |
| --- | --- |
| Mobile first | Default CSS is the small screen; `min-width` adds columns as space grows |
| Breakpoint | The width where the layout changes (`700px`, `1000px` — pick what the design needs) |
| Fluid images | `max-width: 100%` |
| Readable line | `max-width` on text (~60–75 characters) |

**Do not** use a fixed page width of `1200px` with a horizontal scrollbar on phones.

Chrome DevTools: toggle the device toolbar (`Ctrl+Shift+M` / `Cmd+Shift+M`) and drag the width. Watch the grid go from 1 → 2 → 3 columns.

### Pseudo-classes and states

A **pseudo-class** styles an element in a state or a position.

```css
a:hover { text-decoration: underline; }
a:visited { color: #5a3d7a; }
button:focus { outline: 2px solid gold; outline-offset: 2px; }
button:disabled { opacity: 0.5; cursor: not-allowed; }

input:invalid { border-color: crimson; }
input:valid { border-color: seagreen; }

.cards article:nth-child(odd) { background: #f7f9fc; }
.alert:first-child { margin-top: 0; }
```

| Selector | When it applies |
| --- | --- |
| `:hover` | Pointer is over the element |
| `:focus` | Keyboard or click focused it |
| `:active` | Being pressed |
| `:visited` | Link the user has opened (limited properties for privacy) |
| `:disabled` / `:invalid` / `:valid` | Form control state |
| `:first-child` / `:last-child` | Position among siblings |
| `:nth-child(odd)` | 1st, 3rd, 5th… |

Style **hover and focus together** so keyboard users get the same cue:

```css
a:hover,
a:focus {
  color: #0b1f33;
}
```

**Pseudo-elements** (optional extra boxes):

```css
.alert::before {
  content: "Notice: ";
  font-weight: 700;
}
```

`content` is required for `::before` / `::after` to show. Do not put important text only in `content` — screen readers and selectors vary. Prefer real HTML for real copy.

### Variables and transitions

**Custom properties** (variables) live on `:root` and keep a design consistent.

```css
:root {
  --color-brand: #1e3a5f;
  --color-bg: #f4f7fb;
  --space: 16px;
  --radius: 8px;
}

body {
  background: var(--color-bg);
  color: var(--color-brand);
}

.card {
  border-radius: var(--radius);
  padding: var(--space);
}
```

Change `--color-brand` once; every `var(--color-brand)` updates.

**Transitions** smooth a change. Animate color and shadow, not huge layout jumps.

```css
a {
  color: var(--color-brand);
  transition: color 0.15s ease, background-color 0.15s ease;
}

a:hover {
  color: #0b1f33;
}
```

| Property | Job |
| --- | --- |
| `transition` | What to animate, how long, easing |
| `transform` | `translate` / `scale` — cheap to animate |
| `opacity` | Fade |

Avoid transitioning `width`/`height`/`top` on big areas (janky). Prefer `transform` and `opacity`.

Media query for users who asked for less motion:

```css
@media (prefers-reduced-motion: reduce) {
  * {
    transition: none;
  }
}
```

### How CSS connects to HTML and React

HTML still needs the hooks:

```html
<link rel="stylesheet" href="css/styles.css">
<article class="card">...</article>
```

```css
.card { padding: var(--space); }
```

Later in **React**, the same idea is `className`, not `class`:

```jsx
<article className="card">...</article>
```

You can keep a global `styles.css`, or use CSS Modules / styled-components later. The properties you learned (`display`, `flex`, `gap`, `color`) do not change.

DevTools workflow (every bug):

1. Inspect the element
2. See which rules apply and which are crossed out
3. Toggle properties live
4. Copy the winner back into `styles.css`

### Cheat sheet

| Goal | CSS |
| --- | --- |
| Attach file | `<link rel="stylesheet" href="css/styles.css">` |
| Element | `h1 { }` |
| Class / id | `.card { }` / `#notices { }` |
| Nested | `nav a { }` |
| Font + color | `font-family`, `font-size`, `color` |
| Root size | `rem` |
| Include padding in width | `box-sizing: border-box` |
| Inside / outside space | `padding` / `margin` |
| Center a column | `max-width: 960px; margin: 0 auto;` |
| Round + shadow | `border-radius` + `box-shadow` |
| Hide | `display: none` |
| Sticky header | `position: sticky; top: 0;` |
| Row of items | `display: flex; gap: 16px;` |
| Push leftover space | `flex: 1` |
| Equal columns | `display: grid; grid-template-columns: 1fr 1fr;` |
| From 1 to 3 columns | `@media (min-width: 700px) { ... }` |
| Hover / focus | `:hover`, `:focus` |
| Theme token | `:root { --color-brand: #1e3a5f; }` |
| Smooth color | `transition: color 0.15s ease;` |

### Day 8 recap

Flex is one axis. Grid is rows and columns. Media queries change those layouts by width. Variables keep the school brand in one place.

CSS across Days 6–8 is the **look** of every web screen in this course. React will still emit HTML + classes; these same rules apply.

Practice: style the student register page — flex nav, a centered form card, `:focus` on inputs, a two-column layout from `700px` up, and brand colors as CSS variables. Resize the browser and confirm it does not overflow.

[Back to index](#index)

---

## Day 9

**Topic:** JavaScript basics  
**Goal:** Students can attach a script, declare `let`/`const`, work with strings, numbers, and booleans, and read errors in the console.

Quick reference for JavaScript: what it is, how it connects to HTML, and the values you will use every day.

### What JavaScript is

**JavaScript** (JS) is the programming language of the browser. HTML is structure. CSS is look. JS is **behaviour**.

```text
HTML  →  the login button exists
CSS   →  the button looks navy
JS    →  the button does something when clicked
```

JS can:

- react to clicks, typing, and form submit
- change text, classes, and HTML on the page
- remember values (variables, later `localStorage`)
- talk to a server (later `fetch` → Node API)

It **is** a programming language: variables, if/else, loops, functions. Full lessons are Days 9–14. React and Node are still JavaScript.

Run JS in two places in this course:

| Where | Tool | Use |
| --- | --- | --- |
| Browser | Chrome + DevTools Console | Pages, DOM, `fetch` |
| Later, server | Node.js | APIs, files, databases |

Today: browser only. Open DevTools with `F12` or `Ctrl+Shift+J` / `Cmd+Option+J`.

### How to add JavaScript

Three ways. Use an **external** file for real projects — same idea as CSS.

```html
<!-- 1. External (best) — defer waits for HTML, then runs -->
<script src="js/app.js" defer></script>
```

Put that in `<head>`, or put `<script src="js/app.js"></script>` just before `</body>`. Either way the HTML exists before your code runs.

```html
<!-- 2. Internal — in the HTML file, before </body> -->
<script>
  console.log("School Portal");
</script>
```

```html
<!-- 3. Inline — on one element. Avoid for real apps. -->
<button onclick="alert('Hi')">Click</button>
```

| Method | Where | Use |
| --- | --- | --- |
| External | `.js` file + `<script src>` | Whole site. One file, many pages |
| Internal | `<script>` in the HTML | Quick demo on a single page |
| Inline | `onclick=""` on a tag | Tiny demo — not for a whole app |

Same folder idea as [file paths](#file-paths):

```text
project/
  index.html
  css/
    styles.css
  js/
    app.js
```

From `index.html`: `src="js/app.js"`.

**`defer`** = download the file while HTML parses, run it after the document is ready. Use it. Without it, a script in `<head>` can run too early and `querySelector` finds nothing.

JS in the page is **case-sensitive**. `console.log` works. `Console.Log` does not.

### Values and types

Every value has a **type**.

| Type | Example | Meaning |
| --- | --- | --- |
| `string` | `"Asha"` `'10-A'` `` `Hi` `` | Text. Quotes required |
| `number` | `18` `0` `3.5` `-2` | Maths, counts, marks |
| `boolean` | `true` `false` | Yes/no flags |
| `undefined` | (no value yet) | Declared, not set |
| `null` | `null` | Intentionally empty |
| `object` | `{ name: "Asha" }` | Named fields ([Day 11](#day-11)) |
| `array` | `["Asha", "Ravi"]` | Ordered list ([Day 10](#day-10)) |

```javascript
typeof "Asha";   // "string"
typeof 18;       // "number"
typeof true;     // "boolean"
typeof undefined;// "undefined"
```

Strings and numbers are not the same:

```javascript
"10" + 2;  // "102"  (string join)
10 + 2;    // 12     (maths)
```

Convert when you mean maths:

```javascript
Number("10");     // 10
String(10);       // "10"
Boolean("");      // false
Boolean("Asha");  // true
```

`Number("hello")` is `NaN` (**N**ot **a** **N**umber). Check with `Number.isNaN(value)`.

### Variables

A **variable** is a named box that holds a value.

```javascript
const school = "Code Sagara";
let seats = 30;
seats = 29;           // let can change
// school = "Other";  // Error — const cannot be reassigned
```

| Keyword | Reassign? | Use |
| --- | --- | --- |
| `const` | No | Default. Names, lists you mutate in place, functions |
| `let` | Yes | Counts, flags, values that change |
| `var` | Yes (old rules) | Do **not** use. Function-scoped, confusing |

Names: **camelCase**, start with a letter. `studentName`, not `student-name` (that is minus).

```javascript
const studentName = "Asha";
const maxMarks = 100;
let isLoggedIn = false;
```

One statement per line. Optional semicolon; this course uses them.

```javascript
const section = "10-A";
let lateCount = 0;
```

### Operators and strings

**Arithmetic**

| Op | Job | Example |
| --- | --- | --- |
| `+` `-` `*` `/` | Add, subtract, multiply, divide | `7 + 3` → `10` |
| `%` | Remainder | `10 % 3` → `1` |
| `**` | Power | `2 ** 3` → `8` |

```javascript
let marks = 40;
marks += 10;  // 50  same as marks = marks + 10
marks++;      // 51  add one
```

`+` on strings **concatenates** (joins):

```javascript
"Hello, " + "Asha";  // "Hello, Asha"
```

Prefer **template literals** (backticks) so variables sit inside the text:

```javascript
const name = "Asha";
const section = "10-A";
const message = `Welcome, ${name} (${section})`;
```

`${}` only works in backticks, not in `" "` or `' '`.

**Logical / compare** is [Day 10](#day-10). Today remember: `===` is “same value and same type”.

```javascript
10 === "10";  // false
10 == "10";   // true  (avoid — it converts types)
```

Always `===` and `!==` in this course.

### Console and errors

`console.log` prints to DevTools. It does **not** show on the page.

```javascript
const student = "Asha";
console.log(student);
console.log("marks", 40 + 10);
console.log({ student, section: "10-A" });
```

| Method | Use |
| --- | --- |
| `console.log` | Inspect a value |
| `console.warn` | Yellow warning |
| `console.error` | Red error you logged |
| `console.table` | Array or object as a table |

The Console also **runs** code. Type `2 + 2` and press Enter.

When something breaks, the Console shows the **file, line, and message**:

```text
Uncaught TypeError: Cannot read properties of null (reading 'addEventListener')
    at app.js:4
```

That usually means `querySelector` found nothing (wrong selector, or script ran before the HTML). Fix the selector or add `defer`.

`alert("Hello")` pops a blocking dialog. Fine for a 10-second demo. Use `console.log` or page text for real work.

### Day 9 recap

JS is behaviour. Attach it with `<script src="js/app.js" defer>`. Prefer `const`, use `let` when the value must change, skip `var`. Types matter: `"10"` is not `10`. Template literals build strings. The Console is how you see values and errors.

Practice: `js/app.js` on the school homepage — `const` school name, `let` notice count, a template-literal welcome string, `console.log` all three. Break it on purpose (typo a variable) and read the Console error.

[Back to index](#index)

---

## Day 10

**Topic:** Decisions and loops  
**Goal:** Students can branch with `if`/`else`, loop through a list, and store ordered data in an array.

Quick reference for the questions JS asks every day: is this true, and do this for each item.

### Comparisons and logic

Comparisons produce a **boolean**.

| Op | Meaning | Example |
| --- | --- | --- |
| `===` | Equal value **and** type | `section === "10-A"` |
| `!==` | Not equal | `role !== "admin"` |
| `>` `<` `>=` `<=` | Greater / less | `marks >= 40` |
| `&&` | And — both true | `isStudent && feesPaid` |
| `\|\|` | Or — at least one true | `isAdmin \|\| isTeacher` |
| `!` | Not — flip boolean | `!isLoggedIn` |

```javascript
const marks = 72;
const passing = marks >= 40;       // true
const honour = marks >= 75 && marks <= 100;

const isAdmin = false;
const isTeacher = true;
const staff = isAdmin || isTeacher;  // true
```

**Truthy / falsy** — `if (value)` asks “does this count as true?”

Falsy (only these): `false`, `0`, `""`, `null`, `undefined`, `NaN`.

Everything else is truthy: `"Asha"`, `1`, `[]`, `{}`.

```javascript
const name = "";
if (!name) {
  console.log("Name is required");
}
```

Prefer an explicit check when it is clearer: `name === ""` or `marks >= 40`.

### if and else

```javascript
const marks = 72;

if (marks >= 75) {
  console.log("Distinction");
} else if (marks >= 40) {
  console.log("Pass");
} else {
  console.log("Fail");
}
```

Braces `{ }` around each branch. One `if`, any number of `else if`, optional final `else`.

**Ternary** — a one-line choice that **produces a value**:

```javascript
const status = marks >= 40 ? "Pass" : "Fail";
```

Use it for short assignments. Nested ternaries are hard to read — use `if` instead.

**`switch`** — when one value has many exact cases:

```javascript
const day = "Mon";

switch (day) {
  case "Mon":
  case "Tue":
  case "Wed":
  case "Thu":
  case "Fri":
    console.log("School day");
    break;
  case "Sat":
  case "Sun":
    console.log("Weekend");
    break;
  default:
    console.log("Unknown");
}
```

`break` stops the case. Forget it and the next case runs too (**fall-through**). `if`/`else` is enough most days.

### Loops

A **loop** repeats work.

**`for...of`** — walk each item in a list (use this first):

```javascript
const students = ["Asha", "Ravi", "Meera"];

for (const name of students) {
  console.log(`Hello, ${name}`);
}
```

**`for`** — when you need the index or a count:

```javascript
for (let i = 0; i < students.length; i++) {
  console.log(i, students[i]);
}
```

`i` starts at `0` because array indexes start at `0`. `i < length` means “while there is still an item”. `i++` moves to the next.

**`while`** — repeat until a condition is false:

```javascript
let seats = 3;
while (seats > 0) {
  console.log(`Seats left: ${seats}`);
  seats--;
}
```

If the condition never becomes false, the loop never ends. Always change something inside `while`.

| Keyword | Job |
| --- | --- |
| `break` | Leave the loop now |
| `continue` | Skip this round, do the next |

```javascript
for (const name of students) {
  if (name === "Ravi") continue;  // skip Ravi
  if (name === "Meera") break;    // stop at Meera
  console.log(name);
}
```

Do not use `for...in` on arrays (it walks keys, not values, and is meant for objects). Prefer `for...of`.

### Arrays as lists

An **array** is an ordered list. Indexes start at **0**.

```javascript
const notices = ["Sports day Friday", "Fees due", "PTM 10 Oct"];

notices[0];           // "Sports day Friday"
notices.length;       // 3
notices[notices.length - 1];  // last item
```

```text
index    0                      1           2
value    "Sports day Friday"    "Fees due"  "PTM 10 Oct"
```

Change and grow:

```javascript
notices.push("Holiday Monday");  // add at end
notices.pop();                   // remove last
notices[1] = "Fees due Friday";  // replace
```

`const notices` still lets you **change items inside**. `const` blocks `notices = somethingElse`, not `notices.push(...)`.

Empty list: `const scores = [];`

Mixed types work (`[1, "Asha", true]`) but a list of one kind of thing is easier to reason about.

Loop + if together:

```javascript
const marks = [72, 38, 91, 40];
let passed = 0;

for (const score of marks) {
  if (score >= 40) {
    passed++;
  }
}

console.log(`${passed} of ${marks.length} passed`);
```

More array tools (`map`, `filter`, `find`) are [Day 11](#array-methods).

### Day 10 recap

`===` compares. `&&` / `||` / `!` combine booleans. `if`/`else` chooses a path. Loops repeat; `for...of` is the default for lists. Arrays are 0-based lists with `.length`, `.push`, and `.pop`.

Practice: an array of five student marks. Loop and `console.log` Pass/Fail for each. Count how many passed. Then skip anyone with `0` using `continue`.

[Back to index](#index)

---

## Day 11

**Topic:** Functions, objects, and array methods  
**Goal:** Students can write functions that return values, store related data in objects, and transform lists with `map` / `filter` / `find`.

These three pieces are the data shape of React later: a function component, a student object, an array of students.

### Functions

A **function** is a named recipe. Define once, call many times.

```javascript
function greet(name) {
  return `Hello, ${name}`;
}

greet("Asha");  // "Hello, Asha"
greet("Ravi");  // "Hello, Ravi"
```

| Piece | Meaning |
| --- | --- |
| `function greet` | Name |
| `(name)` | **Parameter** — input placeholder |
| `{ ... }` | Body |
| `return` | Send a value **out**. Stops the function |
| `greet("Asha")` | **Call**. `"Asha"` is the **argument** |

No `return` means the function returns `undefined`.

```javascript
function isPass(marks) {
  return marks >= 40;
}

if (isPass(72)) {
  console.log("Pass");
}
```

**Arrow functions** — same idea, shorter. You will see these everywhere in React.

```javascript
const greet = (name) => {
  return `Hello, ${name}`;
};

// one expression: implicit return
const greetShort = (name) => `Hello, ${name}`;
const isPass = (marks) => marks >= 40;
```

One parameter can drop parens: `name => \`Hello, ${name}\``. Zero or 2+ parameters need parens: `() => ...`, `(a, b) => ...`.

Default parameters:

```javascript
function greet(name = "student") {
  return `Hello, ${name}`;
}

greet();  // "Hello, student"
```

### Scope

**Scope** = where a name is visible.

```javascript
const school = "Code Sagara";  // outer

function banner() {
  const label = "Portal";      // inner
  return `${school} ${label}`; // inner can read outer
}

banner();
// console.log(label);  // Error — label does not exist here
```

`let` and `const` are **block-scoped**: visible inside the nearest `{ }`.

```javascript
if (true) {
  const status = "open";
}
// console.log(status);  // Error
```

That is why `var` is trouble (`var` ignores block `{ }` and leaks). Keep using `const` / `let`.

A function can use outer variables. That is normal. If two functions need the same value, pass it as a **parameter** instead of reaching for a distant `let` — easier to test and reuse.

### Objects

An **object** groups related facts under **keys**.

```javascript
const student = {
  name: "Asha",
  section: "10-A",
  marks: 72,
  feesPaid: true,
};
```

Read and write with dot notation:

```javascript
student.name;           // "Asha"
student.marks = 80;
student.absent = false; // add a key
```

Square brackets when the key is in a variable:

```javascript
const field = "section";
student[field];  // "10-A"
```

Keys are strings. Values can be any type — including arrays and other objects.

```javascript
const student = {
  name: "Asha",
  subjects: ["Maths", "Science"],
  address: { city: "Hyderabad", pin: "500001" },
};

student.subjects[0];     // "Maths"
student.address.city;    // "Hyderabad"
```

**Shorthand** when the variable name matches the key:

```javascript
const name = "Asha";
const marks = 72;
const row = { name, marks };  // { name: "Asha", marks: 72 }
```

**Destructuring** pulls keys into variables:

```javascript
const { name, section } = student;
```

A list of objects is the usual app shape:

```javascript
const classList = [
  { name: "Asha", marks: 72 },
  { name: "Ravi", marks: 38 },
  { name: "Meera", marks: 91 },
];
```

`typeof []` is `"object"` (a JS quirk). Check arrays with `Array.isArray(value)`.

### Array methods

These return a **new** array (or a value). They do not replace `for...of`; they replace a loop that was only building another list.

```javascript
const classList = [
  { name: "Asha", marks: 72 },
  { name: "Ravi", marks: 38 },
  { name: "Meera", marks: 91 },
];
```

| Method | Job | Returns |
| --- | --- | --- |
| `forEach` | Run a function per item | `undefined` (side effects only) |
| `map` | Turn each item into something else | New array, same length |
| `filter` | Keep items that match | New, maybe shorter array |
| `find` | First match | The item, or `undefined` |
| `some` / `every` | Any / all match? | `boolean` |
| `includes` | Is this value in the list? | `boolean` (primitives) |

```javascript
classList.forEach((row) => {
  console.log(row.name);
});

const names = classList.map((row) => row.name);
// ["Asha", "Ravi", "Meera"]

const passed = classList.filter((row) => row.marks >= 40);
// Asha and Meera objects

const ravi = classList.find((row) => row.name === "Ravi");

const anyoneFailed = classList.some((row) => row.marks < 40);  // true
const allPassed = classList.every((row) => row.marks >= 40);   // false
```

Chain when it stays readable:

```javascript
const honourNames = classList
  .filter((row) => row.marks >= 75)
  .map((row) => row.name);
```

Mutating helpers you already used: `push`, `pop`, `shift` (remove first), `unshift` (add first). Prefer `map`/`filter` when you are deriving a new list for the screen.

**Spread** copies an array or object (new box, same values):

```javascript
const copy = [...classList];
const withNew = [...classList, { name: "Irfan", marks: 64 }];
const updated = { ...student, marks: 80 };
```

React state updates will look like that: copy, then change.

### Day 11 recap

Functions take arguments and `return` values. Arrow functions are the short form. `let`/`const` live in a block. Objects hold named fields; arrays of objects are typical app data. `map` transforms, `filter` keeps, `find` picks one.

Practice: `classList` of 4 students. Write `isPass(marks)`, `filter` the pass list, `map` to names, `find` one student by name. `console.table` the pass list.

[Back to index](#index)

---

## Day 12

**Topic:** The DOM  
**Goal:** Students can select elements, change text and classes, create a list item in JS, and run code on click.

This is how JS meets the HTML from Days 3–5.

### The DOM

The **DOM** (Document Object Model) is the browser’s live tree of the page. Tags become **nodes** JS can read and change.

```text
document
  html
    head
    body
      h1
      ul
        li
        li
```

HTML is the source file. The DOM is that tree **in memory** after the browser parses it. `document` is the root object.

```javascript
document.title;                 // tab title
document.body;                  // the <body> element
```

Change the DOM → the screen updates. You do not rewrite the `.html` file; you change the live tree.

### Selecting elements

Same selectors as CSS ([Day 6](#selectors)).

```javascript
const heading = document.querySelector("h1");
const loginBtn = document.querySelector("#login");
const cards = document.querySelectorAll(".card");
```

| Call | Returns |
| --- | --- |
| `querySelector("css")` | **First** match, or `null` |
| `querySelectorAll("css")` | A **NodeList** (all matches) |
| `getElementById("login")` | The `#login` element, or `null` |

`null` means “not on the page”. Calling a method on `null` crashes. Guard it:

```javascript
const heading = document.querySelector("h1");
if (!heading) {
  console.error("No h1 found");
}
```

NodeList is not a full array. Convert if you need `map`:

```javascript
const texts = [...document.querySelectorAll(".card")].map(
  (el) => el.textContent
);
```

Or loop:

```javascript
document.querySelectorAll(".card").forEach((card) => {
  card.classList.add("is-ready");
});
```

Need a **hook** in the HTML: `id` for one thing, `class` for a group — from [Day 3](#comments-and-common-attributes).

```html
<h1 id="page-title">School Portal</h1>
<ul id="notices"></ul>
<button type="button" id="add-notice">Add notice</button>
```

### Changing the page

```javascript
const heading = document.querySelector("#page-title");

heading.textContent = "Student Portal";  // text only, safe
heading.innerHTML = "Student <em>Portal</em>"; // parses HTML — careful
```

| Property / method | Job |
| --- | --- |
| `textContent` | Get/set plain text (preferred) |
| `innerHTML` | Get/set HTML inside. Do **not** put user input here (XSS) |
| `classList.add` / `remove` / `toggle` / `contains` | CSS classes |
| `style` | Inline style. Prefer classes |
| `setAttribute` / `getAttribute` | Any attribute (`href`, `hidden`, `disabled`) |
| `hidden` | Boolean show/hide |
| `value` | Input/textarea/select current value |

```javascript
const alertBox = document.querySelector(".alert");
alertBox.classList.add("is-visible");
alertBox.classList.toggle("is-urgent");

const email = document.querySelector("#email");
console.log(email.value);
email.value = "";
```

CSS:

```css
.alert { display: none; }
.alert.is-visible { display: block; }
```

JS toggles the class. CSS owns the look — same split as Days 6–8.

### Creating elements

```javascript
const list = document.querySelector("#notices");

const item = document.createElement("li");
item.textContent = "Sports day Friday";
list.append(item);
```

| Call | Job |
| --- | --- |
| `createElement("li")` | New element, not on the page yet |
| `append(node)` | Add as last child |
| `prepend(node)` | Add as first child |
| `remove()` | Take this element off the page |
| `replaceChildren(...)` | Clear and put these in |

Build from an array ([Day 11](#array-methods)):

```javascript
const notices = ["Sports day Friday", "Fees due", "PTM 10 Oct"];
const list = document.querySelector("#notices");

list.replaceChildren(); // clear

notices.forEach((text) => {
  const li = document.createElement("li");
  li.textContent = text;
  list.append(li);
});
```

`textContent` for the words. If you need a structure (link inside `li`), create each child — do not concatenate untrusted HTML into `innerHTML`.

### Click events

An **event** is something that happened. You **listen**, then run a function.

```javascript
const button = document.querySelector("#add-notice");

button.addEventListener("click", () => {
  console.log("clicked");
});
```

The second argument is a **callback** — a function you pass in, the browser calls later.

The listener receives an **event object**:

```javascript
button.addEventListener("click", (event) => {
  console.log(event.target);  // the element that was clicked
});
```

| Idea | Meaning |
| --- | --- |
| `addEventListener("click", fn)` | Run `fn` on click |
| `event.target` | The element that fired the event |
| `event.preventDefault()` | Stop the default (link jump, form submit) — [Day 13](#form-events) |
| `button.disabled = true` | Stop extra clicks |

`type="button"` on `<button>` so it does **not** submit a form by accident ([Day 5](#forms)).

Put listeners in `app.js` after the HTML is ready (`defer` from [Day 9](#how-to-add-javascript)). Do not put `onclick="..."` in the HTML for course work.

A tiny page:

```javascript
const button = document.querySelector("#add-notice");
const list = document.querySelector("#notices");
let count = 1;

button.addEventListener("click", () => {
  const li = document.createElement("li");
  li.textContent = `Notice ${count}`;
  list.append(li);
  count++;
});
```

### Day 12 recap

The DOM is the live page tree. `querySelector` finds nodes. `textContent` and `classList` change them. `createElement` + `append` build new nodes. `addEventListener("click", ...)` runs your function when the user clicks.

Practice: notices `<ul>` and an Add button. Each click appends a new `<li>`. A second button clears the list with `replaceChildren()`. Toggle an `.is-visible` class on an alert box.

[Back to index](#index)

---

## Day 13

**Topic:** Forms, events, and `localStorage`  
**Goal:** Students can handle submit without a page reload, read fields, listen to input/change, and save a string in `localStorage`.

This is JS on the register form from [Day 5](#day-5).

### Form events

Default submit **reloads** the page and sends the form to `action`. For a JS app, stop that and read the fields yourself.

```html
<form id="register">
  <label for="student-name">Name</label>
  <input id="student-name" name="name" required>

  <label for="student-email">Email</label>
  <input id="student-email" name="email" type="email" required>

  <button type="submit">Register</button>
</form>
<p id="form-status" hidden></p>
```

```javascript
const form = document.querySelector("#register");
const status = document.querySelector("#form-status");

form.addEventListener("submit", (event) => {
  event.preventDefault();

  const data = new FormData(event.target);
  const name = data.get("name");
  const email = data.get("email");

  if (!name || !email) {
    status.hidden = false;
    status.textContent = "Name and email are required.";
    return;
  }

  status.hidden = false;
  status.textContent = `Saved ${name} (${email})`;
  form.reset();
});
```

| Piece | Job |
| --- | --- |
| `submit` | Fires on button or Enter in a field |
| `preventDefault()` | No reload, no navigation |
| `FormData(form)` | Reads every control that has a `name` |
| `data.get("email")` | One field (matches `name="email"`) |
| `form.reset()` | Clear the controls |

You can also read `document.querySelector("#student-email").value`. `FormData` scales better when the form grows.

HTML `required` / `type="email"` still help. JS checks are for extra rules (password length, matching fields) and for when you send JSON later.

Listen to **input** for live feedback:

```javascript
const email = document.querySelector("#student-email");

email.addEventListener("input", () => {
  email.classList.toggle("is-invalid", email.validity.typeMismatch);
});
```

`change` fires when the value is committed (blur on text, pick on select). `input` fires on every keystroke.

### Other events

| Event | Typical on | When |
| --- | --- | --- |
| `click` | button, anything | Pointer click |
| `submit` | form | Submit |
| `input` | input, textarea | Value is changing |
| `change` | select, checkbox, radio | Value committed |
| `keydown` | document, input | Key pressed |
| `DOMContentLoaded` | document | HTML parsed (if you did not use `defer`) |

```javascript
document.addEventListener("keydown", (event) => {
  if (event.key === "Escape") {
    const modal = document.querySelector(".modal");
    if (modal) {
      modal.classList.remove("is-open");
    }
  }
});
```

`event.key` is `"Enter"`, `"Escape"`, `"a"`, … Check `event.target` if you only care when focus is in one field.

**Delegation** — listen on a parent when many children do the same thing (a list of delete buttons):

```javascript
const list = document.querySelector("#notices");

list.addEventListener("click", (event) => {
  const btn = event.target.closest("[data-delete]");
  if (!btn) return;
  btn.closest("li").remove();
});
```

`data-delete` is an HTML **data attribute**: `<button type="button" data-delete>Remove</button>`.

**Timers** (optional):

```javascript
setTimeout(() => {
  status.hidden = true;
}, 3000);  // ms

const id = setInterval(() => {
  console.log("tick");
}, 1000);

clearInterval(id);
```

### localStorage

`localStorage` saves **strings** in the browser. They survive refresh. They do not go to your server.

```javascript
localStorage.setItem("school-theme", "dark");
const theme = localStorage.getItem("school-theme"); // "dark" or null
localStorage.removeItem("school-theme");
```

Objects and arrays must become JSON strings:

```javascript
const student = { name: "Asha", section: "10-A" };

localStorage.setItem("student", JSON.stringify(student));

const saved = JSON.parse(localStorage.getItem("student"));
// saved.name === "Asha"
```

`JSON.parse` throws if the string is not JSON. Guard:

```javascript
function readStudent() {
  const raw = localStorage.getItem("student");
  if (!raw) return null;
  try {
    return JSON.parse(raw);
  } catch {
    return null;
  }
}
```

| Limit | Meaning |
| --- | --- |
| Strings only | Use `JSON.stringify` / `JSON.parse` |
| Per origin | `http://localhost:3000` ≠ a deployed site |
| Visible to JS | Do **not** store passwords |
| ~5MB | Fine for a student object, not for videos |

`sessionStorage` is the same API; it clears when the tab closes.

### Small UI patterns

**Show / hide**

```javascript
function show(el) {
  el.hidden = false;
}
function hide(el) {
  el.hidden = true;
}
```

**Disable while working**

```javascript
button.disabled = true;
button.textContent = "Saving…";
```

**Render a list from data** (one function you call after every change):

```javascript
const notices = ["Sports day Friday", "Fees due"];

function renderNotices() {
  const list = document.querySelector("#notices");
  list.replaceChildren();
  notices.forEach((text) => {
    const li = document.createElement("li");
    li.textContent = text;
    list.append(li);
  });
}

renderNotices();
```

Keep **data in JS** (the array). The DOM is a view of that data. After `push` / `filter`, call `renderNotices()` again. That is the same idea React will use with state.

Save the array:

```javascript
localStorage.setItem("notices", JSON.stringify(notices));
```

On load, read it, then render.

### Day 13 recap

`submit` + `preventDefault` + `FormData` reads a form without reload. `input` / `change` / `keydown` cover the rest. `localStorage` persists strings; JSON packs objects. Keep an array in JS and re-render the DOM from it.

Practice: register form — prevent submit, show a status message, `localStorage.setItem` a JSON student. On refresh, `JSON.parse` and fill a “Last saved: Asha” line. Extra: notices list that saves to `localStorage`.

[Back to index](#index)

---

## Day 14

**Topic:** Async JS and `fetch`  
**Goal:** Students can explain a Promise, use `async`/`await`, `GET` JSON with `fetch`, and say how this talks to a Node API later.

The browser must **wait** for the network without freezing the page.

### Sync vs async

**Synchronous** code runs top to bottom. Each line waits for the one above.

```javascript
const a = 1;
const b = a + 1;
console.log(b);  // 2 — you know this now
```

**Asynchronous** work finishes **later**: network, timers, user clicks. The rest of the page stays usable.

```text
JS:  fetch /api/students
     …page still clicks, types, paints…
later: response arrives → your callback / await continues
```

If `fetch` were sync, the tab would freeze until the server replied.

Events from Days 12–13 are already async: `addEventListener` runs your function **later**, not when you registered it.

### Promises and async/await

A **Promise** is an object for a value that is not ready yet.

| State | Meaning |
| --- | --- |
| pending | Still working |
| fulfilled | Got a result (`then`) |
| rejected | Failed (`catch`) |

```javascript
fetch("https://jsonplaceholder.typicode.com/users/1")
  .then((response) => response.json())
  .then((user) => {
    console.log(user.name);
  })
  .catch((error) => {
    console.error(error);
  });
```

**`async` / `await`** is the same idea, written like sync code. Prefer this in the course.

```javascript
async function loadUser() {
  try {
    const response = await fetch(
      "https://jsonplaceholder.typicode.com/users/1"
    );
    if (!response.ok) {
      throw new Error(`HTTP ${response.status}`);
    }
    const user = await response.json();
    console.log(user.name);
  } catch (error) {
    console.error(error);
  }
}

loadUser();
```

| Piece | Job |
| --- | --- |
| `async function` | Lets you use `await` inside. Returns a Promise |
| `await promise` | Pause **this function** until it finishes. Not the whole page |
| `try` / `catch` | Run `catch` if `throw` or a rejected Promise |
| `response.ok` | HTTP 200–299. `fetch` only rejects on network failure, **not** on 404 |

You can only `await` inside `async` (or a module top level, later). Button handlers:

```javascript
button.addEventListener("click", async () => {
  await loadUser();
});
```

### fetch and JSON

**`fetch`** sends an HTTP request and returns a Promise of a **Response**.

**JSON** (JavaScript Object Notation) is text that looks like a JS object. APIs send JSON. `response.json()` parses that text into a real object/array.

```javascript
async function loadStudents() {
  const response = await fetch("/api/students");
  if (!response.ok) {
    throw new Error(`HTTP ${response.status}`);
  }
  return response.json();  // array of student objects
}
```

**GET** is the default (read). **POST** sends a body (create) — you will use this with Node:

```javascript
async function registerStudent(student) {
  const response = await fetch("/api/students", {
    method: "POST",
    headers: { "Content-Type": "application/json" },
    body: JSON.stringify(student),
  });

  if (!response.ok) {
    throw new Error(`HTTP ${response.status}`);
  }

  return response.json();
}

await registerStudent({ name: "Asha", section: "10-A" });
```

| Piece | Job |
| --- | --- |
| `JSON.stringify(obj)` | Object → string for `localStorage` or a request body |
| `JSON.parse(text)` | String → object |
| `response.json()` | Read body and parse JSON (async) |
| `Content-Type: application/json` | Tell the server the body is JSON |

Render what you got ([Day 12](#creating-elements)):

```javascript
async function showStudents() {
  const status = document.querySelector("#status");
  const list = document.querySelector("#students");

  status.textContent = "Loading…";
  try {
    const students = await loadStudents();
    list.replaceChildren();
    students.forEach((row) => {
      const li = document.createElement("li");
      li.textContent = `${row.name} (${row.section})`;
      list.append(li);
    });
    status.textContent = "";
  } catch (error) {
    status.textContent = "Could not load students.";
    console.error(error);
  }
}
```

Always handle failure on the screen, not only in `console.error`.

Public demo API for practice (no key, fake data): `https://jsonplaceholder.typicode.com/users`.

Opening an HTML file as `file://` can block `fetch` to other sites. Use a small local server (VS Code Live Server, or `npx serve`) when you practise network calls.

### How JS connects to React and Node

```text
Browser JS (today)
  querySelector, addEventListener, fetch
        ↓
React (next)
  still JavaScript: functions, objects, arrays, map/filter
  still fetch (or a library) to talk to the server
  the DOM is updated for you from state
        ↓
Node.js
  JavaScript on the server
  receives fetch POST / GET
  reads/writes MongoDB or SQL
```

What carries forward:

| You learned | In React / Node |
| --- | --- |
| `const` / `let`, `===`, template literals | Same |
| Functions, arrows, `return` | Components are functions |
| Objects + arrays of objects | Props, state, documents |
| `map` / `filter` | Lists on screen |
| `JSON.stringify` / `parse` | API bodies |
| `fetch` + `async`/`await` | Load and save data |
| `import` / `export` (next) | Split files; React components |

```javascript
// you will write this shape soon
export function greet(name) {
  return `Hello, ${name}`;
}

import { greet } from "./greet.js";
```

Browsers need `type="module"` on the script (or a bundler). Node and Vite/React set that up. The language is the same.

Chrome DevTools: **Network** tab shows each `fetch` (status, payload). **Console** shows errors. Use both, like [Day 1](#chrome-devtools).

### JS cheat sheet

| Goal | JS |
| --- | --- |
| Attach file | `<script src="js/app.js" defer></script>` |
| Constant / changing | `const x = 1;` / `let n = 0;` |
| String with values | `` `Hello, ${name}` `` |
| Same value and type | `===` / `!==` |
| Branch | `if (cond) { } else { }` |
| Loop a list | `for (const item of list) { }` |
| Array | `const xs = [];` `xs.push(item)` |
| Function | `function f(a) { return a; }` |
| Arrow | `const f = (a) => a;` |
| Object | `const row = { name: "Asha", marks: 72 };` |
| Transform list | `xs.map((x) => x.name)` |
| Keep some | `xs.filter((x) => x.marks >= 40)` |
| First match | `xs.find((x) => x.name === "Asha")` |
| Select | `document.querySelector("#id")` |
| Text | `el.textContent = "Hi"` |
| Class | `el.classList.add("is-open")` |
| New node | `document.createElement("li")` + `list.append(li)` |
| Click | `el.addEventListener("click", () => { })` |
| Form | `event.preventDefault()` + `new FormData(form)` |
| Save locally | `localStorage.setItem("k", JSON.stringify(obj))` |
| Read locally | `JSON.parse(localStorage.getItem("k"))` |
| HTTP GET | `const data = await (await fetch(url)).json()` |
| Check HTTP | `if (!response.ok) throw new Error(...)` |
| Wait | `async function f() { await promise; }` |
| Errors | `try { } catch (error) { }` |

### Day 14 recap

Sync code waits in line. Async work finishes later so the page stays alive. A Promise is that later value. `async`/`await` plus `try`/`catch` is how you write it. `fetch` loads JSON from a URL; `response.ok` matters. React will reuse functions, objects, arrays, and `fetch`. Node will *be* the URL you call.

JavaScript across Days 9–14 is the **behaviour** of every web screen in this course — including React screens, which are still JS functions rendering HTML.

Practice: fetch `https://jsonplaceholder.typicode.com/users`, render `name` and `email` into a `<ul>`, show “Loading…” then a clear error if the network fails. Extra: a Register button that `POST`s JSON (the demo API will echo it) and `console.log` the result.

[Back to index](#index)

