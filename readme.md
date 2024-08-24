# Git Assignment - <maksymchyk>

a. What is an issue?    
Issues are used to track todos, bugs, feature requests, and more. They are similar to tickets.

b. What is a pull request?  
It is a request to pull updates from your current branch to the main branch, merge updates between branches. It allows proper review and testing before merging different branches.

c. Describe the steps to open a pull request?   
After the changes are staged, commited, and pushed to the github, pull request is started by clicking "Compare and pull request" button under pull requests tab. Add a title and a description of changes to complete the creation of a pull request.

d. Describe the steps to add a collaborator to a repository (share write permissions)   
Go to GitHub Settings-> Access -> Collaborators and teams. Click "Add people" button in the collaborators section, add their usernames and emails and select usernames from a drop down list. Write permissions are given by default. Read or admin permissions can be added in the process. Click "Add" button.

e. What is the difference between git and GitHub?   
Git is a distributed version control system. It allows multiple team members to work on the code simultaneously and track changes efficiently. It also allows doing it locally, and pushing changes to the online server. Github is a related web based platform that adds hosting, online features and collaboration tools to Git.

f. What does git diff do?   
It is a command that shows line by line differences between various states of current repository, like staging, working directory, and between different commits.

g. What is the main branch?     
It is a default primary branch of the repository that contains stable production ready version of the code. It's a base for other branches, target for merging, and usually a point where releases are made from.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?     
It is not recommended for projects where multiple people are working on the project. This practice doesn't enable code review, and allows collaboration conflicts.