this file is adding for important notes

1) If a person git add . means stage change want to remove, first check status (git status) if change added, so need to write (git reset) their stage change will revert
2) suppose he did commit change and then he decide to remove commit then what should he do?
   so need write (git reset HEAD~1), so will back one step, and the commit will revert
3) Second way of reset commit:
this way is very critical, if you did the commit will also reset as well all the changes will wash thats you have finish in code, you will again write code, moral of the story, very carefully apply this command

4) how to see commited change
   command : git log , (git log --oneline) this oneline will show all key in a single line
   after, (reset log d5a0d7a) copy key from log history, that commit which you want to go back
   if want completely go back and revert complete changes, then add ( git reset --hard d5a0d7a) will will wash your current change and go back to that commit
