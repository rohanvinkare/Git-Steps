# <B style="color:Red">About The GIT</B>

### 1. Working Area

Normal Folders And Files Not Cared By GIT

### 2. Tracked Area

Folder And Files GIT Knows About

### 3. Staging Area

Folder And Files GIT Will Upload

### 4. GIT Directory

Folder And Files Uploaded By GIT

# <B style="color:yellow">Steps To Upload Files On GIT</B>

#### <B style="color:orange">1. Working Area</B>

### To initialize git in folder

```
git init
```

### To check status of tracked and untracked files

#### Unselected files Will Appear In Red

```
git status
```

#### <B style="color:orange">2. Tracked Area</B>

### To Select All Files In Current Folder For Upload

```
git add .
```

### To check status of tracked and untracked files

#### Selected files Will Appear In Red

```
git status
```

#### <B style="color:orange">3. Staging Area</B>

### Add Massage For Saving / Committing files

#### Still Files Are Not Uploaded

```
git commit -m "message"
```

#### <B style="color:orange">4. GIT Directory</B>

### Specify Where To Upload The Files

```
git remote add origin https://github.com/rohanvinkare/your-repo-name.git
```

### If repo Already Exists and some one changed it so first pull the changes and then push the changes

```
git pull origin main
```

### Final Step Pushing Into Branch

```
git push -u origin main
```

# <B style="color:yellow">Another Help Full Commands</B>

### Make All Files Untracked

```
git reset
```

### For Files Which We Don't Want To tracked By GIT

#### For that create a file with <B style="color:orange">" .gitignore "</B> extension and add all the files which we don't want to track by GIT in this file

### Setting address of the location where the changes will be pushed to

```
git remote add origin https://github.com/rohanvinkare/your-repo-name.git
```

### Clones/Copies the git all files from internet to your computer

```
git clone https://github.com/rohanvinkare/your-repo-name.git
```

# <B style="color:yellow">Branching Stuff</B>

#### First create a new repoYou have to crete the branch on Git hub website

### To show all Branches In Current Repo Of Git / Github

```
git branch -a
```

### To create a new Branch

```
git branch branch-name
```

### To delete a new Branch

```
git branch -d branch-name
```

### To switch to a branch

```
git checkout branch-name
```

# <B style="color:yellow">Merging Stuff</B>

### Switch to a branch where you want top merge

```
git checkout branch-name

(branch-name -> Branch in which you  want to merge (main))
```

### Get Changes if Anyone Made Change before in this branch

```
git pull origin branch-name

(branch-name -> Branch in which you  want to merge (main))
```

### Merge The Branch Into

```
git branch --merged
git merge branch-name

(branch-name -> Branch you want to merge (first-branch))
```

### Final Step Pushing Into Branch

```
git push -u origin branch-name

(branch-name -> Branch in which you  want to merge (main))
```
