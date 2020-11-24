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


# Git Reset Hard Head
    git reset --hard HEAD

# Git Stash

    git stash save "my_stash"   (Where "my_stash" is the stash name)
    git stash list              (All the stashes are stored in a stack)
    git stash pop stash@{n}     (To apply a stash and remove it from the stash stack)
    git stash apply stash@{n}.  (To apply a stash and keep it in the stash stack). (Where n is the index of the stashed change.)
    
# Clone a repository
    
    git clone <url>
    git remote set-url origin http://github.com/myname/reponame
    ggp
    
# Creating a Branch from a Tag and Checking out to it

    git checkout -b <branch-name> <tag>
    
# Get rid of being asked “Enter passphrase for key ” while doing ssh operation on a remote host

    ssh-add ~/.ssh/id_rsa

# Mongo Installation - Mac Catalina

    https://zellwk.com/blog/install-mongodb/

# Create SSH Key on mac

    https://www.youtube.com/watch?v=XoASOMU8lNk&t=372s
    
    
# SWITCHING FROM TERMINAL (MAC) TO cOMMAND PROMPT (WINDOWS) 

    ls              |              dir
    clear           |              cls
    mkdir           |              mkdir

# Set up Charles - Using Charles from an iPhone

    1. Go to the Settings app
    2. Tap Wi-Fi
    3. Find the network you are connected to and then tap the blue disclosure arrow to configure the network
    4. Scroll down to the HTTP Proxy setting, tap Manual
    5. Enter the IP address of your computer running Charles in the Server field, 
       and the port Charles is running on in the Port field (usually 8888)
    6. Leave Authentication set to Off
    7. All of your web traffic from your iPhone will now be sent via Charles. 
       You should see a prompt in Charles when you first make a connection from the iPhone, asking you to allow the traffic
    8. Remember to disable the HTTP Proxy in your Settings when you stop using Charles, 
       otherwise you'll get confusing network failures in your applications!
    
