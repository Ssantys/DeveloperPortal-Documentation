# Developer Portal Documentation

The Single Point of Truth for the NBG Developer Portal documentation pages. 

## Contribute

We encourage you to contribute to the development of the documentation by following the steps below.

### 1. Pull the documentation you want to change

When you want to make a change or enrich a current file all you have to do is try to edit the file. By clicking the edit button you are forking the project and then you edit the file in your repository. Alternative you can click the fork button at the top right of the github page in order to fork your own copy of the project into your repo-account.

The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. The git pull command is actually a combination of two other commands, git fetch followed by git merge. In the first stage of operation git pull will execute a git fetch scoped to the local branch that HEAD is pointed at. Once the content is downloaded, git pull will enter a merge workflow. A new merge commit will be-created and HEAD updated to point at the new commit.

With the "git branch" command we can see in which branch we are currently on.

The "git fetch" command is basically checking and making sure that updates have occured.

Finally with the "git pull" command we can pull down the updates that have been recently pushed . It is actually merging the updates fetched with the current branch.

You can think of git pull as Git's version of svn update.

### 2. Edit the documentation on your editor of choice (locally)

One of the editors that we suggest is the SwaggerHub. Where the user can create a new API or import and document an API from our swagger collection. Then the user can edit the preffered Swagger and test it for errors or warnings before making a pull request to the repo.

Link for Swaggerhub

https://app.swaggerhub.com/

Link for Apicurio

https://www.apicur.io/

Or if you are using Visual Studio Code there is an extension called OpenAPI (Swagger) Editor

https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi

### 3. Submit a pull request to this repo

When you file a pull request, all you’re doing is requesting that another developer pulls a branch from your repository into their repository. This means that you need to provide 4 pieces of information to file a pull request: the source repository, the source branch, the destination repository, and the destination branch.

These are the steps you have to follow in order to prepare and submit a pull request.

1. Fork the project with the clone command.

Example: git clone https://https://github.com/myNBGcode/DeveloperPortal-Documentation/edit/master/README.md

2. You can navigate to the cloned directory with the cd command

Example: cd README

3. Assign the original repo to a remote called "upstream". The term upstream and downstream refers to the repository. Generally, upstream is from where you clone the repository, and downstream is any project that integrates your work with other works.

Example: git remote add upstream https://https://github.com/myNBGcode/DeveloperPortal-Documentation/edit/master/README.md

2. You can always get the latest changes with the pull command

Example: git checkout master
         git pull upstream master
         
The git checkout command lets you navigate between the branches created by git branch

3. Create a new topic branch to contain your feature or change.

Example: git checkout -b <topic-branch-name>

4. Push your topic branch up to your fork.

Example: git push origin <topic-branch-name>

5. Open a Pull Request with a nice title and description.

6. Finally when the Pull Request is done you can get back into master and delete the topic branch.

Example: git checkout master
         git branch -D <topic-branch-name>

Your request will be reviewed and the documentation, if needed, will be updated. We will celebrate through our channels each and every meaningful contribution however minor it might be.

## Acknowledgments

* developer.nbg.gr
