If you use openssh on git then you need to check your ssh refer to this link: https://help.github.com/en/articles/connecting-to-github-with-ssh

Local:

git init
add .gitignore
git status
git add --all (git add .)
git status
git commit -m "adds .gitignore file"
git status
git log


Master/Origin:

ceate repository
git remote add origin git@github.com:dannyadil/gittest.git
git push -u origin master


Collaborate on github: 

1. Fork (do it from github)
	-> Fork gitinfo from dannyadil to dannysibarani
2. Clone (on git bash)
	-> cd gitinfo
	-> git remote add upstream git@github.com:dannyadil/gitinfo.git

	-> This will now allow you to pull in changes from the source locally and merge them, like so:
		git fetch upstream
		git merge upstream/master
3. 
	