# hello-world
Learning the ropes !!!

Curiously seeking the truth, coding when I can, dancing whether or not I need to. 

Absolute madness.

The following have been helful

### Clone a Git Repo to a Specific tag
    # clone the repo
    $ git clone [repository_to_clone]

    # List and checkout tags
    $ git tag -l
    
    # switch head to your chosen tag
    $ git checkout [tag]

### View git Log
View entire log

    $ git log

View short log
    
    $ git log --oneline


### Undo Commits to invert last commit
    $ git revert HEAD


### Sync fork with original repo
First check origin and add upstream
    
    $ git remote -v
    $ git remote add upstream https://github.com/[OriginalOwner]/[OriginalProject].git

Fetch from upstream
    
    $ git fetch upstream

Checkout your fork's master and then merge changes from upstream into it

    $ git checkout master
    $ git merge upstream/master
    
Add and commit new changes
    
    $ git add
    $ git commit -m "[commit message]

Push changes to your fork

    $ git push origin master
    

### Add/Update Origin (Similar to adding Upstream)
Add origin
 
    $ git remote add origin https://https://github.com/[gitusername]/[gitrepository].git
 
Update origin

    $ git remote set-url origin https://https://github.com/[gitusername]/[gitrepository].git

### Sources
Setup Git

http://swcarpentry.github.io/git-novice/02-setup/

https://www.earthdatascience.org/workshops/intro-version-control-git/basic-git-commands/

https://dev.px4.io/master/en/contribute/git_examples.html#contributing_code

Learning markdown

https://guides.github.com/features/mastering-markdown/

Syncing with upstream/master

https://rick.cogley.info/post/update-your-forked-repository-directly-on-github/

Undoing changes

https://www.atlassian.com/git/tutorials/undoing-changes

