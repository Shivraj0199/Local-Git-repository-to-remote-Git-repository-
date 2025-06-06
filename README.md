## To connect your Git local machine to a GitHub remote repository


**Step 1: Create a Folder on Desktop (eg. Github remote server)**


**Step 2: Open Git Bash in that folder**

```
    Right-click inside the Git local server folder
    Click "Git Bash Here"

```

**Step 3: Set Your Git Identity**

```
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"

```

**Step 4: Create a GitHub Repo to your remote server (eg. my project)**


**Step 5: Initialize Git in Your Local machine**

```
git init

```
**Step 6: Connect to GitHub Remote Repository**


   * Copy your GitHub repo URL
   * HTTPS: https://github.com/yourusername/my-project.git


```
     git remote add origin https://github.com/Shivraj0199/git-testing.git

```

**Step 7: Check Git Status**

```
git status 

```

**Step 8: Create a new file**

```
nano myfile.txt

```

**Step 9: Add all files in your working directory to the staging area**

```

git add "file name"

```

**Step 10: Takes everything you added (git add) and saves it in Git history as a snapshot**

```

git commit -m "initial message"

```

**Step 11: Pushes your code to the remote GitHub repository** 

```

git push -u origin master

```
