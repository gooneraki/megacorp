# megacorp

This repository is a **learning and practice project** completed as part of the  
[Boot.dev – Learn Git 2](https://www.boot.dev/learn/learn-git-2) course.

It simulates working at a fictional enterprise company (“MegaCorp™”) and is designed
to teach **real-world Git workflows** used in professional software teams.

---

## What This Repo Demonstrates

This repository intentionally contains a rich Git history showcasing advanced Git concepts, including:

- Forking and contributing via pull requests
- Merge conflicts and conflict resolution
- Rebase conflicts and history rewriting
- Recovering lost commits using `reflog`
- Squashing commits with interactive rebase
- Safe undoing with `git revert`
- Selective commits with `git cherry-pick`
- Debugging history with `git bisect`
- Temporary work storage with `git stash`
- Working in parallel using `git worktree`
- Versioning releases with annotated tags (SemVer)

The **commit history itself is the primary artifact** of this repository.

---

## Project Structure

The files in this repo simulate an internal enterprise codebase:

- `customers/` — sample customer data used to trigger conflicts and scans
- `orgs/` — partner and organization data
- `scripts/` — shell scripts used for scanning and bisect exercises
- `README.md` — this file

None of the data is real — everything exists purely for learning purposes.

---

## Intended Audience

This repository is useful for:
- Developers learning **advanced Git**
- Reviewing common **team-based Git workflows**
- Interview preparation (being able to *explain* Git, not just use it)
- Demonstrating Git competency to employers

---

## Notes

- This repo rewrites history in several places **on purpose** (e.g. squash, rebase).
- Some commits exist solely to be reverted, cherry-picked, or bisected.
- Do not treat this as a production repository — it is a learning artifact.

---

## Course Credit

Completed as part of:

**Boot.dev – Learn Git 2**  
https://www.boot.dev/learn/learn-git-2

---

## License

Educational use only.  
MegaCorp™ is fictional. Any resemblance to real enterprise software is purely coincidental 😉
