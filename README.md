# pitchinit
template for the structure of gitpitch


## Preparing
1.  Clone this repository and change directory to new cloned directory
```
git clone https://github. com/mzntaka0/pitchinit.git ${new_repo_name}
cd ${new_repo_name}
```

2.  Change remote repository url (First need to create remote repository. e.g.)on Github)
```
git remote set-url origin ${new_repo_url}
```

3.  Initial commit
```
git add . 
git commit -m 'Initial commit'
git push -u origin master
```

4. Open your first slide.
```
# Open the URL below on your browser
https://gitpitch.com/$USER/$REPO_NAME
```

> You must substitute your GitHub account name for $USER and repository name for $REPO_NAME in the above slideshow URL.
