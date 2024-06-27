# LampROS

## Git Hub let's us work in the same folder, while not interfering with each others' work.


-- 

### When you first start, go to a directory of your choice.
## Cloning

```git clone git@github.com:kmsilva00/LampROS.git myfolder```

### the git folder will be inside of myfolder

Open myfolder in vs code.

Originally, you will be in **MAIN BRANCH**

**MAIN** is the current progress of the project

your **BRANCH** is your current progress

### You can checkout the available **BRANCHES** with git branch

You can change your current **BRANCH** with ```git checkout branch```

### You can now work freely without risk of breaking anything 

## CHanging contents inside your branch

Some basic Git commands are:
```
git status
git branch
``` 
first change to (your) branch

```git checkout currentBranch```

- to add changes 
```
git add .                                       - adds all (new)files
git commit -m "comment descrbing addition"      - commits the changes
git push origin currentBranch                   - pushes changes to current branch
```


# Never work direcly on main, use your own branch

### Once your branch is stable and you wish to make your branch, the main branch then you need to merge.


## Merging

Go to main

``` 
git checkout main

Make sure your main branch is up to date with the remote repository

git pull origin main

git merge feature-branch

git push origin main
```

# TLDR Commands 

git pull - pulls current changes , download and update the cloud files to ur local files

git push - push current changes, upload and updates the local files to cloud [ don't forget to add and commit your changes before pushing]

git branch - Shows available branches

git checkout - let's you change working branch

