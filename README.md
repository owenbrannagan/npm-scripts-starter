# git-demo

First we set up our github repo - this is our REMOTE repository.

Then we create our web project folder (this will be our LOCAL git repository).

CD INTO FOLDER and initialise the folder as a git using: `git init`

Next we add our files eg index.html, js files, css etc, and we need git to know about these files and that we want to commit our changes. To do this: `git add <your file or files>`.

If you want to add all files to the staging area to be included in the commit, do: `git add .`

Now we commit the changes using ` git commit -m "A specific message about the changes which you choose" `

Change the name of the local branch to main:
`git branch -M main`

Add the github repo as a remote:
`git remote add origin main`
`git remote -v` Check the origin remote ahas been added.

Finally push the changes on the main branch to origin
`git push -u origin main`


to check where you are

ls
pwd
cd
# npm-scripts-starter
