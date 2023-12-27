## Git Basic Commands
## Create Repo on GitHub and clone it locally:
###
### git clone (github link) -> to get clone from remote repo to local repo
### git status -> what is the status os every file
### git add (fileName.extention) or * -> * means all files , git add to staging area
### <!-- ## git reset HEAD (fileName.extention) -> remove from staging area --> -> old version
### git rm --cached (fileName.extention) -> remove from staging
### git commit -m "commit message" -> we can do more than one commit with different changes
### git branch -> get the name of the existing branch
### git remote -v -> get the name of the existing remote -> origin is the remote of GitHub
### git push (remoteName) (branchName) -> git push origin master
### git pull origin -> fetch and merge local and remote repo


## Creating Public Key Commands
###
### ssh-keygen -t rsa -b 4096 -C "user@gmail.com" -> ssh-keygen:secure shell-generate key, rsa: Rivest Shamir Adleman algorithm, bits number,
### type "C:\Users\dell\.ssh\id_rsa.pub" -> to access the key 
### then add it to github
### ssh -T "git@github.com" -> to connect through the key


## Git Basic Commands
## Create Repo on locally first and connect it to remote repo:
###
### git init -> intializing empty repo
### git add .
### git commit -m "first commit"
### git remote add origin git@github.com:nouraa17/git_commands.git -> use ssh link (of the public key)
### git push -u origin master -> -u = pull and push
###
###


### mkdir (folderName) -> create folder
### type nul > (fileName) -> create file



