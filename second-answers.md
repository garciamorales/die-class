Answer to quesion 1. 
! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/garciamorales/die-class.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Answer to question 2. Yes, there was a conflict reported
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (8/8), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 5 (delta 2), reused 5 (delta 2), pack-reused 0
Unpacking objects: 100% (5/5), done.
From https://github.com/garciamorales/die-class
   d249d89..9df827f  master     -> origin/master
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.

Answer to question 3:
* master

Answer to question 4:
* header
  master

  Answer to question 5: 
  
Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----        8/27/2020  11:53 AM            302 .gitignore
-a----        8/27/2020   2:26 PM             15 2ndfilepaola.md
-a----        8/27/2020   6:27 PM              0 die.cc
-a----        8/27/2020   1:00 PM            954 first-answers.md
-a----        8/27/2020   3:00 PM            190 README.md
-a----        8/27/2020   1:00 PM           1044 second-answers.md

Answer to question 6: 
Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----        8/27/2020  11:53 AM            302 .gitignore
-a----        8/27/2020   2:26 PM             15 2ndfilepaola.md
-a----        8/27/2020   9:37 PM           1172 die.h
-a----        8/27/2020   1:00 PM            954 first-answers.md
-a----        8/27/2020   9:37 PM             53 newfilePaola1.md
-a----        8/27/2020   9:35 PM            202 README.md
-a----        8/27/2020   1:00 PM           1044 second-answers.md

Answer to question 7: They are not merged
Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----        8/27/2020  11:53 AM            302 .gitignore
-a----        8/27/2020   2:26 PM             15 2ndfilepaola.md
-a----        8/27/2020   9:37 PM           1172 die.h
-a----        8/27/2020   1:00 PM            954 first-answers.md
-a----        8/27/2020   9:37 PM             53 newfilePaola1.md
-a----        8/27/2020   9:35 PM            202 README.md
-a----        8/27/2020   1:00 PM           1044 second-answers.md


PS Microsoft.PowerShell.Core\FileSystem::\\home.ohio.edu\home\pg748418\Desktop\die-class> git
checkout master
Already on 'master'
Your branch is up to date with 'origin/master'.
PS Microsoft.PowerShell.Core\FileSystem::\\home.ohio.edu\home\pg748418\Desktop\die-class> git
merge implement
Merge made by the 'recursive' strategy.
 README.md | 4 +---
 die.cc    | 0
 2 files changed, 1 insertion(+), 3 deletions(-)
 create mode 100644 die.cc
PS Microsoft.PowerShell.Core\FileSystem::\\home.ohio.edu\home\pg748418\Desktop\die-class> ls


    Directory: \\home.ohio.edu\home\pg748418\Desktop\die-class


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
-a----        8/27/2020  11:53 AM            302 .gitignore
-a----        8/27/2020   2:26 PM             15 2ndfilepaola.md
-a----        8/27/2020   9:47 PM              0 die.cc
-a----        8/27/2020   9:37 PM           1172 die.h
-a----        8/27/2020   1:00 PM            954 first-answers.md
-a----        8/27/2020   9:37 PM             53 newfilePaola1.md
-a----        8/27/2020   9:47 PM            190 README.md
-a----        8/27/2020   1:00 PM           1044 second-answers.md
