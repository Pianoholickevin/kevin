Notes about git:
to initialize:
git init

to get status:
git status

to add a file to git
git add {filename}

Files first enter the unstaged area, they are red

Then files enter the staged area, they are green

Then files are committed, they are officially in git

To commit a file:
run: git commit
write your message
save and quit with :wq

to show the logs of changes run:
git log

to see the actual changes run:
git show {git_hash}

to checkout any branch or commit in time, run:
git checkout {git_hash or branch_name}

SSH keys:
we have a public key and a private key
we give the public key to github and we keep the private key safe on our computer

When you create a new branch, to push run:
git push -u origin {branch_name}