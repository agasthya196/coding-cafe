# Lab 1 - Notes

1. `pwd` printed `/home/bhard/coding-cafe`, which is the absolute path to my current working directory.
2. `ls -a` showed hidden files/directories starting with a dot (like `.` and `..`), which plain `ls` hides.
3. The `Mode` / permissions column (e.g., `drwxr-xr-x`) indicates file types (`d` for directory) and read, write, execute permissions for user, group, and others.
4. `coding-cafe/week02` works because it is a relative path starting from the current directory rather than the root directory.
5. `mv` moved the `README-backup.md` file into the `week01` directory first, and then renamed `README-backup.md` to `old-readme.md`.
6. There are 16 folders listed on my PATH variable.
7. My python lives at `/usr/bin/python3`.
8. Paths may differ if Python was installed using a different path or package manager.
9. The shell said `pyton: command not found` because `pyton` is not an executable file located in any folder on my PATH[cite: 1].
10. `.venv` did not appear in plain `ls` because its name starts with a dot, making it a hidden directory[cite: 1].
11. The prompt changed by displaying `(.venv)` at the beginning to show the environment is active[cite: 1].
12. `which python3` now points to `/home/bhard/coding-cafe/.venv/bin/python3`, showing that activation prepended `.venv/bin` to the front of PATH[cite: 1].
13. `requests` (along with dependencies like `urllib3` and `certifi`) appeared in the second `pip list`[cite: 1].
14. After `deactivate`, `which python3` points back to system Python at `/usr/bin/python3`[cite: 1].
15. In `man ls`, the `-R` flag (equivalent to `-Recurse`) recursively lists directory contents including all subdirectories[cite: 1].
16. `Ctrl + C` sends an interrupt signal to stop a running command, whereas `Ctrl + D` sends an End-Of-File (EOF) marker to exit interactive shells[cite: 1].