# DemoRepo

PS C:\Users\zac22\Documents\~Programming\Level1\program_Stuff\Lessons\RepoDemo\DemoRepo> git checkout -b featureLogIn 
Switched to a new branch 'featureLogIn'

PS C:\Users\zac22\Documents\~Programming\Level1\program_Stuff\Lessons\RepoDemo\DemoRepo> git branch
* featureLogIn
  main
  myNewBranchZac

PS C:\Users\zac22\Documents\~Programming\Level1\program_Stuff\Lessons\RepoDemo\DemoRepo> git log --oneline --all
e6a782e (HEAD -> featureLogIn, origin/main, origin/HEAD, myNewBranchZac, main) added word world and made a comment
d5b1ce1 staged additions
aa50f4c Initial commit

PS C:\Users\zac22\Documents\~Programming\Level1\program_Stuff\Lessons\RepoDemo\DemoRepo> git merge featureLogIn
Already up to date.

PS C:\Users\zac22\Documents\~Programming\Level1\program_Stuff\Lessons\RepoDemo\DemoRepo> git branch --merged
  featureLogIn
* main
  myNewBranchZac

PS C:\Users\zac22\Documents\~Programming\Level1\program_Stuff\Lessons\RepoDemo\DemoRepo> git branch --no-merged

PS C:\Users\zac22\Documents\~Programming\Level1\program_Stuff\Lessons\RepoDemo\DemoRepo> git branch -d featureLogIn
Deleted branch featureLogIn (was e6a782e).