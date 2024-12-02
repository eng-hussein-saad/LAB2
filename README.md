![Photo](ilovegit.png)

Notice that the default branch here is master not main.

To remove branches locally:
  we use : git branch -d dev.
           git branch -d test

To remove branches remotely:
  we use : git push origin :dev
           git push origin :test


To checkout another branch without commit changes and without losing work we use : git stash
                                                                                   git checkout <targetBranch>
                                                                                   git stash pop

  or if we want to checkout and discard our work we can use: git checkout -f <targetBranch>.

To list tags we use: git tag

To delete Tag locally: git tag -d v1.7

To delete remote Tag : git push origin --delete v1.7
  
