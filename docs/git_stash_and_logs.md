# Git Stash and Log Commands

## Git Log Commands
1. **Viewing the Commit History:**
   - git log
   Displays the commit history with details like commit hash, author, date, and commit message.
   - git log --oneline
   Shows each commit in one line with a short hash and commit message.
   - git log --pretty=format:"%h -an, %ar : %s"
   Shows the abbreviated commit hash, author name, relative time, and commit message.
   - git log -p
   Displays the commit history along with the patch (diff) for each commit.
   - git log --graph
   - git log --reverse
   - git log --decorate 
   Last three log commands show almost the same result as git log 

2. **Git Stash Commands**
    Make uncommitted changes to the file 
    - git stash (To save temporarily)
    - git stash list (To see stash list)
    - git stash apply (To reapply the stash changes)
    - git stash push -m "Temporary changes stash" (To temporarily save the changes)
    - git stash drop "stash@{0}" (To drop the stash)