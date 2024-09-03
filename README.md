# Git Assignment - HimeshiS

a. What is an issue?
It is a feature on GitHub that allows us to track requested changes and features in a software project. When creating an issue, a task list can be added that can be checked off by team members as the tasks are completed. Issues are a helpful tool for project management and collaboration among teams working together on software development.

b. What is a pull request?
It is a feature in GitHub that allows developers to request changes from one branch of a repository to be merged into another branch, typically the main branch. In software development, different branches are created to enable team members to work on separate features at the same time. Pull requests are a collaborative feature that allows the team to review the new code, test it and discuss any issues before merging the changes onto the main branch. 

c. Describe the steps to open a pull request?
Navigate to the repository on GitHub where you want to create the pull request and click on the 'Pull requests' tab (third from left). Click on the green 'New' button in the top right of the Pull requests page which opens up a page titled Compare changes. Use the drop-down menus to select the main branch of the repository on the left hand side of the arrow and the branch being merged on the right hand side of the arrow. This ensures that the pull request is being created to merge the branch in question into the main branch of the same repository. Once the branches are selected, GitHub will show a comparison of the changes between the two branches that you can review to ensure accuracy. You can add a description and any other information to the description box. Click on the 'Create pull request' button to submit the pull request. 

d. Describe the steps to add a collaborator to a repository (share write permissions)
Navigate to the repository on GitHub and click on the Settings tab (furthest right). On the menu on the left, there are a list of settings that can be manipulated and under 'Access', click on the 'Collaborators' button. In the resulting page, there is a green 'Add people' tab under Manage Access header. Clicking on it will allow GitHub users to be searched by their username or email address. Select the user you would like to add and confirm by clicking on 'Add user to repository'. The user will receive the invitation via email. They will also be able to view the request if they navigate to the repository. Once accepted, the newly added collaborator should be able to write to and modify content in the repository.  

e. What is the difference between git and GitHub?
Git is a version control system that tracks changes in files and coordinates changes made by multiple people to the files. It is a command-line tool that runs locally on your computer and can perform tasks such as committing and merging new changes, creating branches, fetching the most recent version of the files from the remote repository, etc. GitHub is a graphical interface for git and eliminates the need for command-line usage. It is web-based and has additional features such as issues, pull requests and other project management tools. Given that the repositories are hosted online in GitHub, it allows easy access to files and enables collaboration among team members. 

f. What does git diff do?
git diff is a command used to show differences between two versions of a file in a git repository. When used without any arguments, it shows unstaged changes in your current working directory compared to the last commit. This command is useful for tracking changes in files, between two commits or between branches. 

g. What is the main branch?
The main branch is the default and primary version of a git repository. When developers work on specific aspects of a project, they create new branches to avoid making changes directly to the main branch. Instead, the other branches are used to write new code and only changes tested and reviewed by the team as stable are incorporated into the main branch to maintain stability of the product. In a git repository, settings can be put in place to avoid changes being made by accident or without review to the main branch. 

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
It is not good practice to push changes directly onto the main branch, especially in collaborative projects. The main branch contains the primary state of a repository and any untested changes made to the main branch could cause a software product to not work as expected.
