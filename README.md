# gitCooperationExercise
Finish this tutorial with **bash commands** is recommended, while you can use  **GUI** as well. 

Just enjoy it.:)

##Mission 1
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

- `git remote add origin <url>` : add a new remote repo named origin

- `git config --global core.autocrlf true` : if on Windows, just do it.

## Mission 2
Try git commands with some text work.
Now we have `reqdoc4.0.md` in our repo, use your favorite editor to add more discriptions.

- `git commit -m "<message>"`  : commit your change with a concluding message.
- `git checkout -- <filename>` : abandon all changes made to this file since last commit.
 




