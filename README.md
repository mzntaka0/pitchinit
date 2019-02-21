# pitchinit
template for the structure of <a href='https://gitpitch.com/'>gitpitch</a>


## Preparing
### 1.  Clone this repository and change directory to new cloned directory
```
git clone https://github. com/mzntaka0/pitchinit.git ${new_repo_name}
cd ${new_repo_name}
```

### 2.  Change remote repository url (First need to create remote repository. e.g.)on Github)
```
git remote set-url origin ${new_repo_url}
```

### 3.  Initial commit
```
git add . 
git commit -m 'Initial commit'
git push -u origin master
```

### 4. Write down your slide on PITCHME.md  
How to write PITCHME.md with Gitpitch: <a href='https://gitpitch.com/docs/'>docs</a>  

### 5. Open your first slide.
```
# Open the URL below on your browser
https://gitpitch.com/$USER/$REPO_NAME
```

> You must substitute your GitHub account name for $USER and repository name for $REPO_NAME in the above slideshow URL.


## Gitpitch desktop launch
> You need to subscribe gitpitch. See detail <a href='https://gitpitch.com/'>here</a>.  
> Either needed to install docker and docker-compose(>ver1.22.0) and log in to docker hub(run `docker login`).

```
docker-compose up -d
```
Then you can see your slide on your browser. Default link: <a href='http://localhost:9000'> http://localhost:9000</a>  

See detail <a href='https://gitpitch.com/docs/pro-features/desktop-launch/'>here</a> about Gitpitch desktop with docker.
