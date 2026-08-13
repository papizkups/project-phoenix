Project Phoenix Progress Log

Day 1 - July 1, 2026

✓ Created Project Phoenix folder
✓ Created project structure
✓ Created roadmap, goals, and progress files
✓ Checked PC specifications

PC:
- Windows 10 Pro
- Intel Core i3-7100U
- 8 GB RAM
- SSD

Status:
Project Phoenix officially started.

# Project Phoenix Progress Log

## Day 2
- Learned basic terminal navigation.
- Practiced `pwd`, `ls`, and `cd`.

## Day 3
- Installed and configured VS Code.
- Installed Git and Git Bash.
- Learned what Git Bash is and why we use it.

## Day 4
- Practiced navigating directories.
- Created and explored the Project Phoenix workspace.
- Became comfortable moving around the filesystem.

## Day 5
- Learned `mkdir`.
- Learned `touch`.
- Learned `mv` for renaming and moving files.
- Renamed the Project Phoenix folder correctly.
- Began thinking about commands instead of memorizing them.

## Day 6
- Initialized my first Git repository.
- Learned what `.git` is.
- Understood tracked vs. untracked files.
- Learned `git status`.
- Learned `git add`.
- Made my first Git commit.
- Learned how Git records project history.

## Day 7
- Learned how to view commit history with `git log`.
- Learned to use `git log --oneline` for a compact history.
- Understood commit hashes and why every commit has a unique ID.
- Learned what `HEAD` represents.
- Created my second Git commit by updating the progress log.

## Day 8
- Learned how `git diff` compares changes.
- Understood the difference between the Working Directory, Staging Area, and Repository.
- Learned `git diff --staged`.
- Learned that `git add` captures a snapshot of a file at that moment.
- Practiced reading Git diff output.

## Day 9
- Learned how to use `git restore`.
- Safely discarded unwanted changes.
- Understood that `git restore` restores files to the last committed version.
- Learned that restoring the Working Directory does not automatically change the Staging Area.

## Day 10
- Learned how to inspect commits with `git show`.
- Learned that every commit has a unique commit hash.
- Compared commits using `git diff <commit1> <commit2>`.
- Created a personal Git Cheat Sheet.
- Understood that a file can appear in both "Changes to be committed" and "Changes not staged for commit" if it's edited after being staged.
- Learned that Git may open the `less` viewer and that pressing `q` returns to Git Bash.

## Day 11
- Learned how to unstage files with `git restore --staged`.
- Practiced moving files between the Working Directory and the Staging Area.
- Understood that `git restore` restores the Working Directory.
- Understood that `git restore --staged` restores the Staging Area.
- Strengthened my understanding of Git's three areas: Working Directory, Staging Area, and Repository.

## Day 13
- Learned that `git show <commit>:<file>` displays an old version of a file without changing it.
- Distinguished between Git commands that inspect history and those that modify it.
- Learned that `git diff <commit1> <commit2>` compares entire project snapshots.
- Strengthened my understanding of Git as a snapshot-based version control system.

## Day 14
- Learned what Git branches are and why they are useful.
- Created and switched to my first branch using `git switch -c`.
- Learned that branches are pointers to commits.
- Learned that uncommitted changes belong to the Working Directory, not a branch.
- Practiced switching between `main` and `experiment`.
- Learned how to merge a branch into another branch.
- Learned the difference between fast-forward and non-fast-forward merges.

## Day 15
- Learned how to safely delete a merged branch using `git branch -d`.
- Learned that deleting a branch removes the branch pointer, not the commits it points to when those commits remain reachable.
- Practiced creating branches with `git switch -c`.
- Learned the difference between `git branch`, `git switch`, and `git switch -c`.
- Learned why temporary feature branches are commonly deleted after merging.

## Day 16
- Connected the local Project Phoenix repository to GitHub.
- Learned what a Git remote is and why `origin` is the conventional remote name.
- Learned `git remote` and `git remote -v`.
- Learned the difference between fetch and push.
- Successfully pushed Project Phoenix to GitHub using `git push -u origin main`.
- Learned about upstream/tracking branches.
- Learned the difference between `git fetch` and `git pull`.
- Practiced fetching a remote commit without changing the local working tree.
- Used `git pull` to integrate a remote change into the local branch.
- Learned why diverged local and remote histories may require merging, rebasing, or conflict resolution.

## Day 17
- Learned what merge conflicts are and why they occur.
- Created a deliberate merge conflict between main and a feature branch.
- Used `git status` to identify an unmerged/conflicted file.
- Examined Git conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`).
- Resolved the conflict by choosing the appropriate version.
- Used `git add` to mark the conflict as resolved.
- Completed the merge with a merge commit.
- Learned that merge commits preserve both lines of development.
- Deleted the completed feature branch with `git branch -d`.
- Pushed the merged history to GitHub.