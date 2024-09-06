### Issue with the CSLogin:
The fiber between our machine and the authentication server is dropping 5% of the packets, so the authentication server is complaining and not allowing it through.

## Intro to Git/GitHub
GitHub is a hosting service that uses Git to upload and store projects and files.
* Projects in GitHub are stored as Repositories (Repos)

Steps:
1. Make a Repo in GitHub
2. Clone the Repo to a local machine (git clone https://github.com/bozrem/repo)
3. Make changes
	1. If you need to add something, do ```git add file.c```
4. ```git commit -m "your message about the commit"```
	1. This command commits any changes or added/removed files to the LOCAL repo
5. ```git push```
	1. Sends your commits to GitHub


## Questions
1. I'm used to the IDEs where I need to stage my specific changes, do I need to do that with CLI git or are all of my changes to the files that were already recognized as part of the project committed?
2. If you (professor) makes a repo with skeleton code for us to clone, if we cloned, changed, committed and pushed, would we be able to change the code in your repo?
3. I know that having a lot of commits can seem like a "flex" but how often and important should our commits be? I use my notes app connected to my class repos, but would people view my daily commits negatively?