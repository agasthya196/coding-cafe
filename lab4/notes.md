# Lab 4 - Notes

1. The `--global` flag applies the user name and email configuration to all Git repositories under your user account on this machine. If you leave it out, Git only sets the configuration for the current local repository[cite: 1].
2. Running `ls -a` revealed the hidden `.git` folder[cite: 1]. Inside `.git` are Git's internal tracking files, configuration settings, branch pointers, and object database storing all commit history[cite: 1].
3. Git offers to track your project files and folders (such as `README.md`, `week01`, and `week02`)[cite: 1]. The `.venv` folder contains thousands of third-party library files that you did not write[cite: 1].
4. The `.venv` directory and all its internal subdirectories disappeared from the untracked files list[cite: 1]. The `.gitignore` file itself now appears as untracked[cite: 1].
5. `.gitignore` should be committed because it tells everyone working on the repository which files and folders to ignore[cite: 1]. If it is not committed, other collaborators will not share the same ignore rules[cite: 1].
6. `README.md` moved from "Untracked files" to "Changes to be committed"[cite: 1]. In the three-places model, it moved from the Working Directory into the Staging Area (Index)[cite: 1].
7. Git printed the target branch (`main`), the short commit hash, the commit message, and file change statistics showing the number of files changed and lines inserted[cite: 1].
8. The first seven characters are the short commit hash (SHA-1 identifier)[cite: 1]. They serve as a unique ID to reference that specific commit snapshot in history[cite: 1].
9. The four steps of the cycle are: edit files -> check status (`git status`) -> stage changes (`git add`) -> commit changes (`git commit -m`)[cite: 1].
10. `README.md` uses a special name and root placement because code hosting platforms like GitHub automatically render it on the repository's front page as project documentation[cite: 1].
11. `gh auth login` saved a secure authentication token locally on your machine[cite: 1]. This token handles Git credentials automatically so you do not need to type a password when pushing[cite: 1].
12. `README.md` is displayed on the front page because GitHub automatically detects and renders the root `README.md` file as formatted HTML[cite: 1].
13. No, running `git push` copied your local commits to GitHub without altering your local commit history[cite: 1].
14. A private repository exists on GitHub's cloud servers with full version history accessible to authorized collaborators[cite: 1], whereas a non-existent repository does not exist on cloud servers at all.