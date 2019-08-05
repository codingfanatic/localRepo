# localRepo
*The steps needed to push a locally created project to a new Github repository. This tutorial assumes you have Git installed, know how to create a git commit, and have experience creating repos on Github.*

Most developers who are new to Git only know how to work on projects **after** cloning from Github. But what if you want to push a local repo to Github? 

Fear not! I have the steps below. (video coming soon!)

**What you'll need open:**
A terminal window

**TIP** You can also use Visual Studio Code for its terminal as well. I leave this up to you.

Android Studio, or whichever IDE you're using to generate a new project.

Your browser of choice open to your dashboard at https://github.com/

Step 1: Create a new project locally
> At the Android Studio intro screen, create a new project.

>**TIP** Use camelback casing and make it one word. This will be the name of our repo on Github.

> Save it to a directory of your choosing (ex: localRepo)

Step 2: Create a new Github repo for your project
> Navigate to your Github dashboard and create a new repository

>**IMPORTANT** Make sure the new repo name matches that of your project. 

> Click the green **Clone or download** button and copy the URL of your newly created Github repo

Step 3: Use git in the terminal to push your project to Github
>**TIP** In Visual Studio Code open the terminal using Ctrl + `

> Change to the parent directory of your project using the cd command 

> **Ex:** If your proejct directory is in *user/workspace*, use the command cd user/

> Enter the commands below to complete this step. 

>**TIP** Do not include parentheses for your URL. Just paste it as is.

> git init yourRepoName

> cd yourRepoName

> git remote add origin (URL copied from Github)

> git pull origin master

> git add --all

> git commit 

> Enter your custom commit message and exit the editor

> git push --set-upstream origin master

Step 4: Refresh the page in Chrome and marvel at your works.

Hopefully this helped! I've also included a link to this video on my YouTube channel below. Peace and blessings. (COMING SOON) 
