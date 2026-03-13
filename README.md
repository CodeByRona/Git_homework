# Git History & Recovery Homework
## 🛠️ Tasks Completed in this Repository:

1. **Repository Initialization:** Created a local Git repository and added `project.txt`.
2. **Commit History Cleanup:** Squashed multiple unclear commits ('update', 'stuff', 'final') into a single, meaningful commit using Git reset/amend.
3. **Mistake Simulation & Recovery:** - Created a mistake commit and intentionally performed a hard reset to "lose" it.
   - Successfully tracked down the lost commit hash using `git reflog`.
4. **Branching:** Created a new branch named `recovered-branch` to restore the lost commit safely.
5. **Git Alias:** Created a custom global alias (`git hist`) for a better visual representation of the commit log (`log --graph --oneline --all`).
6. **Tagging:** Tagged the clean, final version on the `master` branch as `v1.0`.

To see the custom visual history tree, you can run the following alias locally:
`git hist`
