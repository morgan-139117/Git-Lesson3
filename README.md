# Git-Lesson3
This is a place I learn and practice Git.

This is an example of Cherry-pick to remove a unwanted submit from anywhere of the working tree. 


  477  git reset --hard b7ad0
  478  git cherry-pick 13ede
  479  git cherry-pick --continue
  480  git status
  481  git cherry-pick --cont
  482  git cherry-pick 4c48be
  483  git status
  484  git status
  485  git cherry-pick --continue
  486  git cherry-pick 7ce78
  487  git cherry-pick e9ed5
  488  git cherry-pick 76dab
  489  git cherry-pick 62fff
  490  git cherry-pick dd916
  491  git cherry-pick 870f9
  492  git push origin master
  493  git status
  494  cat 1.txt


When you pick a cherry which jump from working tree, you need to manually edit the conflicts. 
