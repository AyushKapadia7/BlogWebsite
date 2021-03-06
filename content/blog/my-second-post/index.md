---
title: Create Github Repository
date: "2021-09-07T23:46:37.121Z"
---
Everyone knows you can not store all of your projects locally on computer. You might have to put your projects online for your later reference and for other’s as well. You can do that with the help of Git and Github.

Github is the place where you can put your projects that are local right now in your computer to online on Github and Git is the means to do that. So you can do that in your Command Prompt(cmd) or VSCode Terminal.

So first things first you need to have Git bash downloaded in your computer and you must have your own Github account where you can have your projects listed.


Start with creating new repository on Github. You can add your README and gitignore files while creating a new repository in your VSCode(any text editor). Or you can also add them after you have pushed your repository on Github. Every command mentioned below has to be done in your directory that you want on Github.

To initialize your local directory as a Git repository you will have to type this in your terminal.
```js
$ git init
```

After initializing, if you want to see the status of files whether a file has been deleted or modified you can see that by this command.

```js
$ git status
```

Now you have to add your files in your new local repository which stages them for commit. You can write this command if you want to add files individually.

```js
$ git add YOUR_FILE
```

If you want to add all of your files in your directory at one time then go with below command.

```js
$ git add .
```

After you have staged/added your files in your local repository, you will have to commit those files. Commit is similar to saving files in your account. So everytime you make changes in your files you will have to add and commit those changes. The “-m” below means the message while commiting your files that can depend on the new changes you made.

```js
$ git commit -m "First Commit"
```

In your Github repository at the top you will see Quick Setup Page, there you will see a remote repository URL. Adding that remote URL in your command prompt you will then be able to push your local repository to your remote repository. You can either use HTTPS or SSH.

```js
$ git remote add origin <REMOTE_URL>
```

The last thing is to push the changes in your local repository to Github. As its name suggest it 
pushes the changes in your local repository up to the remote repository you specified as the origin.

```js
$ git push origin main
```

After all these commands if you go on Github Account you will see your new repository with all of your files listed. After making changes in your file you will have to commit those changes. And in 
command line you can see the number of commits you have made on one repository by the below command.

```js
$ git log 
```

And Thats How Its Done.