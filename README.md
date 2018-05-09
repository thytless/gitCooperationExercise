# gitCooperationExercise #
Finish this tutorial with **bash commands** is recommended, while you can use  **GUI** as well. 

Just enjoy it.:)

## Mission 1 ##
### Step 1
Install Git.

### Step 2
Right click a prepared directory and choose **Git Bash Here** or **Git GUI Here**.I am going to discuss the bash way in Windows only.

### Step 3
- `git clone <url>` 

Init your new repo with a remote repo.And you are now in the branch **master**.

Our remote repo : git@github.com:thytless/gitCooperationExercise.git

### Step 4
Some necessary configurations.

- `git config --global user.name "<Your Name>"`
- `git config --global user.email <Your Email Address>`
- `git config --global core.autocrlf true` : if on Windows, just do it.

Caution: `--global` option will change the global git configuration on your computer, e.g on Windows, in "C:\\Users\\???\\.gitconfig".

- `git remote add origin <url>` : add a new remote repo named origin

## Mission 2
- `git checkout -b <New Branch Name>`：Create your new branch and switch to it.

## Mission 3
Try git commands with some text work.
Now we have `reqdoc4.0.md` in our repo, use your favorite editor to add more discriptions.

- `git status` or `git st` : File info and command advice.
- `git add <filename>` : add this (unstaged) file to index.Necessary before commit.
- `git commit -m "<message>"`  : commit your change with a concluding message.
- `git commit -a -m "<message>"` : add all unstaged file into index, then commit.
- `git checkout -- <filename>` : abandon all changes made to this file since last commit.
- `git checkout <commit>`：return to a former commit due to commit logs.

[Learn more](https://git-scm.com/book/zh/v2/Git-%E5%9F%BA%E7%A1%80-%E8%AE%B0%E5%BD%95%E6%AF%8F%E6%AC%A1%E6%9B%B4%E6%96%B0%E5%88%B0%E4%BB%93%E5%BA%93)

## Mission 4
After finishing your work in your own branch, it's time to merge it into the master branch, and push it to remote repository, through which we will perhaps encounter and fix some conflicts.

### Step 1
- `git pull origin master`：First, get the lastest version of master branch.

### Step 2
- `git merge <Your Branch Name>`：Second, merge your branch into master.If you only made insertions and deletions, according to recursive strategy git will automatically complete it.Otherwise, git will use '>>>', '===' and '<<<' to mark conflict contents in your files.Discuss with your colaborators, delete useless contents, and commit it.Congratulations, you've successfully fix these conflicts!

### Step 3
- `git push origin master`：Finally, update your work into remote repository.

Basic tutorial finishes here. 
 


 




