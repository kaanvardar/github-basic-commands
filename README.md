# Github Essential Commands

1. If you want to access *pre-created* github repo **into github**;
- open terminal go any folder and then type *git clone git@github.com:kaanvardar/demo.git
- then go inside the folder using *ls* *cd demo*
- you can edit the files as usual then check *git status* to ensure which files have been changed
- you can add the files then use the command *git add demo.py* or (for every single file *git add .*)
- check again *git status*
- commit the changes using *git commit -m "Added demo.py" -m "Added demo.py and changes in README.md"*
- push the changes *git push*

2. If you want to access *pre-created* github repo into **local machine**;
- go inside de the folder in your local machine using **cd** command 
- type **git init**
- check **git status**
- type **git add .** to add all files in your local machine to github repo you can check with **git status** 
- go github.com then create a repo with same name
- then commit with **git commit -m "created README" -m "some text"**
- type **git remote add origin git@github.com:kaanvardar/demo.git**
- type **git remote -v**
- type **git push**