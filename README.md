# My First Repo 👋

Welcome! This is a practice repository for learning how **Git** and **GitHub** work.
You can't break anything here, so have a go.

## What is Git?

Git keeps track of every change made to a set of files. Each saved change is called a
**commit**. A commit records:

- **what** changed
- **who** changed it
- **when** it was changed
- **why**, in the commit message

A folder tracked by Git is called a **repository** (or **repo**). You're looking at one now.

## Words you'll need

| Word | What it means |
|------|---------------|
| **Repository (repo)** | A project folder that Git is tracking |
| **Commit** | A saved snapshot of your changes, with a message explaining them |
| **Fork** | Your own copy of someone else's repo, on your GitHub account |
| **Branch** | A separate line of work, so you can try things without changing `main` |
| **Pull request (PR)** | Asking the owner of a repo to pull your changes into theirs |

---

## Your tasks

### 1. Fork this repo

Click the **Fork** button at the top right of this page, then click **Create fork**.
You now have your own copy at `github.com/YOUR-USERNAME/My-First-Repo`.

> Check that your username is at the top left of the page before you edit anything.
> From here on you're working on **your fork**, not the original.

### 2. Fill in your About Me page

1. Open [`about-me.md`](about-me.md).
2. Click the ✏️ pencil icon to edit it.
3. Replace the blanks with your own answers.
4. Click **Commit changes...**
5. Write a short message that says what you did, such as `Fill in my about me page`.
6. Click **Commit changes**.

That's your first commit!

### 3. Add a line to the story

Open [`story.md`](story.md) and add **one sentence** to the end of the story. Commit it with a
message such as `Add a sentence to the story`.

### 4. Look at the history

Go back to the main page of your fork and click the **commits** link (the clock icon near the
top of the file list). You'll see:

- the commits that were already in the repo before you forked it
- **your** new commits at the top

Click on one of your commits. Lines in **green** were added and lines in **red** were removed.

### 5. Add your name to the class list

Open [`class-list.md`](class-list.md) and add your name to the bottom of the list. Commit it.

### 6. Send a pull request (optional)

Want your name on the **original** repo's class list? Open a pull request:

1. On your fork, click **Contribute** → **Open pull request**.
2. Check the changes look right.
3. Click **Create pull request**.

Your teacher can then review your changes and merge them in.

---

## Bonus: using Git on the command line

If you have Git installed, try the same thing from a terminal:

```bash
# Download your fork to your computer
git clone https://github.com/YOUR-USERNAME/My-First-Repo.git
cd My-First-Repo

# Make a change, then see what Git noticed
git status

# Stage the change and commit it
git add class-list.md
git commit -m "Add my name to the class list"

# Send your commit back up to GitHub
git push

# See the history
git log --oneline
```
