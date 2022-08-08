# ShellScripts

## gitcb
A command to see the relative history between branches 

Usage:
```
gitcb [-s tbranch][-c] [branch] 
  -s: compare to tbranch only
  -c: show the last common commit
  branch: compare from specific branch (if omitted, compare from branch currently checked out)
  ```
Example:
```
$ gitcb -c
master:                Ahd| Bhd  Lst Cmm
           origin/b1    0+|  0-        -
           origin/b2    1+| 21-  8cd1016
           origin/b3    0+| 22-  8cd1016
       origin/master    0+|  0-        -
```
