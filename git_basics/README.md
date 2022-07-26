`diff` file1 file2 - find difference between 2 files (`diff -u` file1 file2 - to find lines which differ in two files)  
`<` - line was deleted  
`>` - line was added  
`a` - added, `c` - changed  
`git log` - review the commit history  
`git log -p` - review the commit history with details of changes  
`git show commitId` - info about commit and associated patch  
`git config -l` - to look at config  
`checkout` (for unstaged "undoos") and `reset` (for staged "undos") are generally used for making local or private 'undos'. `revert` is considered a safe operation for 'public undos' as it creates new history which can be shared remotely and doesn't overwrite history remote team members may be dependent on.  
`git commit --amend` - allows us to modify and add changes to the **most recent** commit. Avoid for public commits as would create mess.
`git merge --abort` - If there are merge conflicts (meaning files are incompatible), --abort can be used to abort the merge action.
