# Git Cheat Sheet

## git status
**Question it answers:**
What is the current state of my project?

**When I use it:**
Before and after almost every Git operation.

---

## git diff
**Question it answers:**
What exactly have I changed?

**Compares:**
Working Directory ↔ Staging Area

---

## git add
**Question it answers:**
Which changes should be included in my next commit?

**Think of it as:**
Putting files into the staging area.

---

## git commit -m "message"
**Question it answers:**
Create a permanent checkpoint.

**Think of it as:**
Saving a snapshot with a meaningful label.

---

## git log
**Question it answers:**
What is the history of my project?

---

## git show
**Question it answers:**
Show one commit in detail.

**Displays:**
- Commit hash
- Author
- Date
- Commit message
- The changes introduced by that commit

---

## git restore
**Question it answers:**
How do I discard uncommitted changes?

**Warning:**
Only restores the Working Directory. It can permanently discard uncommitted edits.

---

## Git uses `less`

Some Git commands open a viewer called `less` for long output.

Common commands:
- `git log`
- `git show`
- `git diff`

Useful keys:
- `q` → Quit and return to Git Bash
- `Space` → Next page
- `b` → Previous page
- `/` → Search

## Things That Tricked Me
- `git log`, `git show`, and long `git diff` outputs may open the `less` viewer.
- Press `q` to return to Git Bash.

Branches let me experiment without disturbing main.

git switch -c <branch> → create a branch and switch to it.
git switch <branch> → switch to an existing branch.
git branch → list branches.
git branch -d <branch> → safely delete a merged branch.

git fetch → downloads remote information without changing the current branch.
