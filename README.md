androidToy
==========
This project shows how to pushing an existing project to gitHub

	First enable the git: Team-> Share Project, then select a local repo for this project
	Then do the initial commit: Team-> commit, or shell to the dir and do `git add .` `git commit -m "initial commit"`
	Then link the local repo to remote gitHub repo: `git remote add origin https://github.com/flamearrow/CCWeibo.git`
	Then tells git which branch you want to connect your project to(need first pull, then push): `git pull origin master` - pull from master,`git push -u origin master` - push to master

	Note: the eclipse project may not pointing to the root of a repo, but pointing to a dir under a repo, which means a repo might have multiple projects.
