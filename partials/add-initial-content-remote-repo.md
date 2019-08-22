### Guidance on committing existing code to a new remote repository


Good resource: [Adding an Existing Project to Github using the command line](https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/)


1. Create blank Github repo through website. 
2. cd to new local directory to turn into repository containing existing code to check in to Github for the first time
   * Make sure you don’t “accidentally” commit any passwords or sensitive info in your initial commit!

```
git init
git add .
git commit –m “first commit message”
git remote add origin REMOTE_REPO_URL (copy and paste from Github website quick setup link)
git remote –v
git push origin master
```
