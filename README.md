# git-course
Git tutorial command and test, personal use.

### Start
```git
// clone the repo
git clone https://github.com/neerajsinghsonu/git-course.git
// go to the folder
cd git-course
// retrieve the latest meta-data info from the original 
// (yet doesn't do any file transferring. It's more like 
// just checking to see if there are any changes available)
git fetch
// fetch and download content from a remote repository and immediately
// update the local repository to match that content
git pull
// state of the working directory and the staging area.
// It lets you see which changes have been staged, 
// which haven't, and which files aren't being tracked by Git
git status
```

### Add
this line added by following commands
```git
// add change file in git
git add README.md
// commit your change into got
git commit -m "first commit from local"
// push your changes onto git
git push
```
### Update
this line updated by following commands
```git
// add change file in git
git add README.md
// commit your change into got
git commit -m "first update from local"
// push your changes onto git
git push
```
### Create Push Tags
this line added post create a tag in git
```git
// create a new tag
git tag v1.0
// check created tag in local
git tag
// create tag with message/label
git tag -a v1.1 -m "this tag has a label"
// push created tag to remote
git push origin v1.0
```

