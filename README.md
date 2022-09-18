## Creating a new repository using _GIT_ via *Visual Studio Code Terminal*

##### 1. Create a folder

-Run this on the terminal.: 
git init

##### 2. Than create a file (fileName.extension)

-*Note:* Every time you create or make changes to a file it need to go through this three{3} steps:
i. *STAGE* the file
ii. *COMMIT* the file and
iii. *PUSH* it to the repository

##### 3. Add file to *STAGE*:
-Run this on the terminal.: 
git add fileName.extension

##### 4. After you have _stage_ the file, *COMMIT IT*:
-Run this on the terminal.: 
git commit -m "type your commit message!"

##### 5. Now rename your branch to *main*:
-Run this on the terminal.: 
git branch -M main

##### 6. Next you link your *local repository* to your *remote repository*:
-Run this on the terminal.: 
git remote add origin https://github.com/UserName/NameOfTheProject.git

##### 7. Finally you can now *PUSH* your file to the remote repository:
-Run this on the terminal.: 
git push -u origin main

#### Wow!!! you have just push your file to your remote repository (:

##### Now if you want to make some *Changes* go back to your *Visual Studio Code*:
##### 1. After making the _changes_ to the file, you *STAGE* it again:
-Run this on the terminal.: 
git add fileName.extension

##### 2. Then type your *COMMIT* message!:
-Run this on the terminal.: 
git commit -m "Commit message!"

##### 3. Lastly *PUSH* your _changes_ to the remote repository:
-Run this on the terminal.: 
git push

#### Wow!!! you have just push your *Changes* to your remote repository (: