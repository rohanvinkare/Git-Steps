# About The GIT

### 1. Working Area

Normal Folders And Files Not Cared By GIT

### 2. Tracked Area

Folder And Files GIT Knows About

### 3. Staging Area

Folder And Files GIT Will Upload

### 4. GIT Directory

Folder And Files Uploaded By GIT

# Steps To Upload Files On GIT

#### 1. Working Area

### To initialize git in folder

```
git init
```

### To check status of tracked and untracked files

#### Unselected files Will Appear In Red

```
git status
```

#### 2. Tracked Area

### To Select All Files In Current Folder For Upload

```
git add .
```

### To check status of tracked and untracked files

#### Selected files Will Appear In Red

```
git status
```

#### 3. Staging Area

### Add Massage For Saving / Committing files

#### Still Files Are Not Uploaded

```
git commit -m "message"
```

##### 4. GIT Directory

### Specify Where To Upload The Files

```
git remote add origin https://github.com/rohanvinkare/test.git
```

### Final Step Pushing Into Branch

```
git push -u origin main
```
