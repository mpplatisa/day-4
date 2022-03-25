- GIT:
    GIT IS NOT SAME AS GITHUB!!!!!!
Github is a website, which collects code AS TEXT.  You cannot run a project from the Github website.  It is for storage purposes only*.

Git is one of several (although arguably the most frequently used) VERSION CONTROL SYSTEMs, meaning it helps teams of developers working on the same code organize the project and build a system of checks to prevent breaking-changes from being introduced.

Git works by downloading, or "cloing" a version of the "main" repo, or "branch", to an individual's local machine.  From there, any changes made by the developer can be saved, or "committed", and then the developer may update, or "push", changes to the code back up to Github, thus allowing other members of the team to work with that updated code.

There are two(2) primary reasons you may want to use a version control system:  
    - Maintain team cohesiveness while working on a project
    - To save your own work

Remember Super Mario Bros. III?  There was a level that was entirely power-boosters, and everyone would save their game right before that level in case later on they ran out of extra lives/flowers/Yoshi's/etc.  Git allows developers to "save the game".  It will save you a LOT of time and debugging headaches if you develop good "commit" practices now.

*Github actually has many advanced features, includinng website deployment(covered next week), integrations, user management, etc, but it does not run applications pushed to Github.


- Common Git Commands:

code . - Typing this into the terminal will open the current directory/folder in VS Code (may not work for all users).

git init - Will initialize a repository for the project, allowing for git commands.

git status - Will display the status of the files in your repository.

git add . - This command will track all of the files IN THE DIRECTORY/FOLDER YOUR TERMINAL IS CURRENTLY OPENED TO.

git commit -m "enter your message here" : Will commit, or "save" the status of all of the files you began tracking when you executed "git add .".

git push origin main - Will push your commited changes to the online Github repo.  This may require some setup.

git log - Will show the history of your git commits with an identifying log ID#.

git reset --hard <git log number here, no carrots> - Will revert your project back to the state it was in at the selected git log ID#.

git pull - Will update your project with the most recent version pulled into Github.

git clone <https link copied from the green 'Code' button on Github, no carrots> - This will make a copy of the repository on your local machine.  You may need to install additional modules(programs); consult the repo's Readme.md.

- Pull Request

A "pull request" is made through the Github online website, and is used when TEAMS have individuals working on different "branches", ie, local versions of code which may have been altered by a developer.  Branching will not be a major concern if you are working on a project by yourself, and it can be confusing if you are new to Git, so we will not be coving it in detail.  However it should be noted that "pull request" is the desciption of the process by which a developer REQUESTS that a project's manager merge, or "PULL", the changes the developer made into the official code base.

- Forking vs Cloning

FORKING a repo will create a copy of the repo ON YOUR PERSONAL GITHUB ACCOUNT.  This is ideal for when you would like to copy a repo from someone else and then work on it on your own, without attempting to make pull requests to the owner of the repo.

CLONING a repo will create a copy of repo ON YOUR LOCAL MACHINE.  Pushing changes to Github will notify the repo's owner, and will not be merged without a pull request.  This is ideal if you are on a team working on the same code, or if you simply want to save your code onto Github and then copy it onto a different local machine.

FORKING & CLONING is a good thing to do if you are using another Github project as a template that you plan to customize and build out.  Fork the project to your Github account using the website, and then clone the project onto your computer.  Now only you will see the changes you push.

- VS Code has all of the Git commands in the left-hand sidebar.  Select the icon that has three(3) circles with two(2) lines.  If you hover over the icon a tag will appear that says "Source Control (^↑G)", and then you can click on it to open the sidebar.

- DETELE OR MAKE PRIVATE OLD/UNSUSED REPOS THAT ADD CLUTTER TO YOUR GITHUB ACCOUNT.  Remember, this account represents your professional portfolio as a developer AS WELL as the place where you keep all of your stuff.  Don't make a potential employer sort through all of your "hello world" projects to find one good repo-- keep it clean!  You can change project setting from within the repo's "Settings" menu.


#####  Bootstrap #####

See Examples