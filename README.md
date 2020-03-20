# Developer Portal Documentation

The Single Point of Truth for the NBG Developer Portal documentation pages. 

## Contribute

We encourage you to contribute to the development of the documentation by following the steps below.

### 1. Pull the documentation you want to change

The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. The git pull command is actually a combination of two other commands, git fetch followed by git merge. In the first stage of operation git pull will execute a git fetch scoped to the local branch that HEAD is pointed at. Once the content is downloaded, git pull will enter a merge workflow. A new merge commit will be-created and HEAD updated to point at the new commit.

With the "git branch" command we can see in which branch we are currently on.

The "git fetch" command is basically checkning and making sure that updates have occured.

And the "git pull" command we can pull down the updates that have been recently pushed . It is actually merging the updates fetched with the current branch.

You can think of git pull as Git's version of svn update.

### 2. Edit the documentation on your editor of choice (locally)

One of the editors that we suggest is the SwaggerHub. Where the user can create a new API or import and document an API from our swagger collection. Then the user can edit the preffered Swagger and test it for errors or warnings before making a pull request to the repo.

### 3. Submit a pull request to this repo

When you file a pull request, all you’re doing is requesting that another developer pulls a branch from your repository into their repository. This means that you need to provide 4 pieces of information to file a pull request: the source repository, the source branch, the destination repository, and the destination branch.

(...)

Your request will be reviewed and the documentation, if needed, will be updated. We will celebrate through our channels each and every meaningful contribution however minor it might be.

## Acknowledgments

* developer.nbg.gr
