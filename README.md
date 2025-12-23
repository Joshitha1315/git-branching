


 🔹 Level 1

This level focuses on using **relative references** (like `HEAD~3`) to move around commits and to update branches based on your current position in the commit history.
I practiced commands to safely update branch pointers using direct commit references.
<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/cab94b15-886c-4678-ac14-a48f737502ac" />


📌 Commands used:

```bash
git checkout main
git checkout C1
git checkout C0
git branch -f main HEAD~3        # Force main to point at a relative commit
git checkout bugFix
git branch -f main HEAD~3
git checkout C5
git checkout C0
git branch -f command
git checkout C1
git checkout C0
git rebase bugFix
git rebase bugFix C0
```

---

 🔹 Level 2 

This level explores how to **undo or revert commits** safely. I used `git revert`, `git reset`, and different checkouts to reach the goal state.
The idea is to reverse changes from pushed or local commits without rewriting public history when possible.
<img width="1440" height="900" alt="Screenshot 2025-12-17 at 11 09 35 AM" src="https://github.com/user-attachments/assets/09349d02-b682-4776-b85a-5e36285db738" />




📌 Commands used:

```bash
git checkout C2
git checkout C1
git checkout C3
git rebase C3
git rebase C1
```
