# Oh-My-Zsh

    ga       |     git add
    gaa      |     git add --all
    gapa     |     git add --patch
    gb       |     git branch
    gcam     |     git commit -a -m
    gcb      |     git checkout -b
    gcm      |     git checkout master
    gcd      |     git checkout develop
    gcmsg    |     git commit -m
    gco      |     git checkout
    gcp      |     git cherry-pick
    gd       |     git diff
    gdca     |     git diff --cached
    gf       |     git fetch
    gfa      |     git fetch --all --prune
    gfo      |     git fetch origin
    ggl      |     git pull origin $(current_branch)
    ggu      |     git pull --rebase origin $(current_branch)
    gl       |     git pull
    gm       |     git merge
    gp       |     git push
    gst      |     git status
    gsta     |     git stash save
    gstaa    |     git stash apply
    gstd     |     git stash drop
    gstl     |     git stash list
    gstp     |     git stash pop
    gstc     |     git stash clear
    ga       |     git add
    ga       |     git add


# Git Stash

    git stash save "my_stash"   (Where "my_stash" is the stash name)
    git stash save "my_stash"   (All the stashes are stored in a stack)
    git stash pop stash@{n}     (To apply a stash and remove it from the stash stack)
    git stash apply stash@{n}.  (To apply a stash and keep it in the stash stack). (Where n is the index of the stashed change.)
    
