# Testing out Git Commands 
#### (This is an Assignment, please don't judge)

## Follow these steps to create and manage a repo with mostly the Command prompt.


### 1. Best is to start off with a empty folder and open command prompt in there. Begin by typing:
```
git init
```
### This should totally create a .git folder for you. now you can go ahead and code and put them into files. while you are at it, you might want to add a .gitignore file. This file can contain files you dont want git to manage. Just add the file names and follow them with spaces. 

### 2. Once done , you need to add the files: Use this command:
```
git add <filename>
```
### Fun fact , if you want to add the entire folder just go:
```
git add .
```
### Oh no.. Did you add a file you were not supposed to add? Use this command:
```
git rm <filename>
```

### 3. Done? Then lets check it out: Use this command to check the file status :
```
git status
```

### 4. If you are not already a git user, chances are you haven't set your user id and name. No worries, instead of using GUI we shall do it in terminal itself using git config command:
```
git config --global user.email "my@emailaddress.com"
```
### And Also :
```
git config --global user.name "My Name"
```

### 5. Now let's connect our repo with a remote repo...Cuz why not?
```
git remote add origin https://github.com/acccount_name/repository_name.git
```
### Now we check what a mess we made:
```
git remote -v
```
### you should be able to see (push) and (fetch) commands available if everything was as planned

### 6. Letes learn how to make branches because commiting to the _* main *_ is to _* mainstream *_
### To create a new branch all you gotta do is:
```
git branch <branch_name>
```
### NOTE: THIS JUST CREATES A BRANCH AND DOESN'T CHANGE YOUR BRANCH
### Now lets check it.
```
git branch -a
```
### Did you just create too many branches? No worries you can delete them as well, just use:
```
git branch -d <branch_name>
```
### 7. Oh YES!! We need to switch to that branch! So yep, the command for that is :
```
git checkout <branch_name>

```
### you can even create a new branch and switch to it in one command :
```
git checkout -b staging
```
### 8. Finally you want to merge your changes to the main, so all you have to do is :
```
git merge <branch_name>
```
### 9. Now what if I want to plagiarize using command prompt? No probs, all you gotta do is:
```
git clone <remote_URL>
```
### 10. Now for pulling from a repository :
```
git pull <branch_name> <remote_URL/remote_name>
```
### 11. Now for pushing into a repository:
```
git push <remote_URL/remote_name> <branch>
```
### 12. To summon the 'Log-Sabha' all you have to do is use the git log command.
```
git log
```
### This shall show all the changes since the beginning

#### These commands should be enough for now. If its not I shall be adding more. Thank you!
