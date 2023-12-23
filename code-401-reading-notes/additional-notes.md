# Git Practice

## Git Merge
- The process of merging enables combining updates in two different branches.
- ex. Updates in Branch A can be combined into updates in Branch B.
- Code: ```git checkout branch-b```
```git merge branch-a```

## Git Rebase
- Similar to merge but creates a linear commit history for a cleaner look.
- Limited use cases because it restructures the commit history, potentially making it appear that the original branch history is altered. 
- The original commits still exists, but is not as identifiable than a git merge. This can be challenging in collaborative environments where others may have based their work on the original branch.