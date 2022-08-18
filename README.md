# CMPG-323-Overview-34443126
This repository is an overview of all the projects am going to be doing this semester including the portfolio of evidence. I will only use this repository it will help keep track of my CMPG323 work through the semester to avoid any confusions.

# Project and Repository Structures.

![Diagram_Agile](https://user-images.githubusercontent.com/111059100/185374293-70e8bb70-819b-441e-be1e-3a1b42c4cace.PNG)

# Branching strategies.
I will build new branches off of the repository's default branch. I will then work on them branch independently for my repository modifications when updating my project for progress. When I have finished updating, I will submit a pull request to the main branch in order to merge the modifications made in the new branch(es) into the main branch. After a pull request has been merged, I will then delete the head branch as it will no longer needed.

# The Use of .gitignore File
There are files usually on the local machine creasted by the system which I would not like to commit to my repository, and any other file specific to me. Those file will be stored in a .gitignore file that In created and committed in the root directory of my repository. Even if the file is remote/online, I will track it and add it to the .gitignore file.

# Storage of Credentials and Sensitive Information
GitHub lets me create Personal Access Tokens that I can use in place of my password when authenticating over HTTPS for both Git and GitHub. Major benefits includes putting my Github_PAT in the git credential store, and use the credentials package. This allows me to use the same authentication token for HTTPS remotes in git to authenticate with the GitHub API.
When retrieving or publishing Github HTTPS remotes, command line Git will automatically try to authenticate with this token because it is saved in the credential store under the github.com domain.
