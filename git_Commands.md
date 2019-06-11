1. go to new repsitory
	a.give repository name
	b.intialize readme file
	c. for now only this much
2.create a folder for git repositories

## Inside Git Bash CLI

3. go to that folder(it works similar to linux command)
 ex. cd /c or cd /d or cd /d/git
  
# ONlY ONE TIME CONFIGURATION FOR THIS FOLDER
# BEGIN
## To configure 'git' folder to github account follow the following steps
4.git config --global user.name "username"
   ex. git config --global user.name "krishnayele"  //username

5.git config --global user.email "youremail@domain.com"
   ex. git config --global user.email krishnayele@gmail.com  // email no need to put quotes
# END
# EVERY TIME FOR NEW REPOSITORY

## To clone the repository 
### go to github account in your repository click on "clone or download"

6. copy the link 
7. use command
	git clone (url/link)
	ex. git clone https://github.com/krishnayele/TestWindowsConnection-git.git

## This will copy all the content from git repository to the dedicated git folder

-------------------------------------------------------------------------------------------------------------------------------------
# SOME INDEPENDENT STEPS NOW TO ADD NEW FILE AND MAKE CHANGES IN REPOSITORY 
# TO UPLOAD THE FILE FROM COMPUTER TO GITHUB ACCOUNT

1. Create any file you are working on in the repository folder.
	ex. myFile.txt
### in bash 
2. we can use ls command to check list of files present in current repository folder
3. Now to add "myFile.txt. to the git repository online use 
	git add filename
	ex. git add myFile.txt
### Before adding it github account online we need to commit
4. use 
      git commit -m "commit comments" yourfileName
	ex. git commit -m "my first commit" myFile.txt
$You can use "git status" command to check status anytime

### Now to transfer your file to github account
5. to push the file use
	git push -u origin master

# IT MAY ASK GIT ACCOUNT Username and Password FOR FIRST TIME
# Now the file will be visible to you in github account
------------------------------------------------------------------------------------------------------------------------------------



