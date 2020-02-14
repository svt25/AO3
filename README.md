# AO3

GIT => version control system for tracking changes in computer files and coordinating work on those files among many people.

GITHUB => a collaboration platform for developers. GitHub makes it easier for teams to collaborate on projects.

Repository => used to organize a single project and can contain folders, files, images, videos, etc.

Clone => downloading a copy of the source code from source control.

Commit => saved changes, usually contains a brief description of why this change was made.

Push => sending your committed changes to a remote repository.

Pull =>  command that permits you to propose your changes should be merged into the master branch.

Branch => a different version of a particular repository. Branching allows for people to work on different versions of a repository at the same time.

Merge => takes contents of source branch and integrates them with the target branch.

Merge Conflict => conflict that usually occurs when your current branch and the branch you want to merge into the current branch have diverged.

Fetch => command that downloads commits, files, etc. from a remote repository into your local repository.

Remote => common repository that all team members use to exchange their changes.

AN INTRODUCTORY TUTORIAL TO GIT AND GITHUB:
1. First, install git (https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) and then create a GitHub account (https://github.com/).

2. Create a repository by using a terminal after downloading git. Type the command git init to initialize a git repositoru.

3. Add a blank file to the repository using the touch <filename> command. 

4. To add a file to a commit, use the command git add <filename>.
  
5. To create your first commit, run the command git commit -m. You've created a new commit!

6. Now, let's create a new branch. Run git checkout -b <my branch name>. Use the command git branch to ensure the branch was created.
  
7. Now, let's create a repository on GitHub. Click the green "+ New repository" button.

8. Add the name of your repository and an option description.

9. We can push a commit into our branch in the GitHub repo. To do this, run the command git push origin yourbranchname.

10. Let's create a pull request. Then, merge the pull request by pressing the "merge pull request." Use git log to see all the commits made!

11. You're finished!

REFERENCES:
https://www.freecodecamp.org/news/an-introduction-to-git-merge-and-rebase-what-they-are-and-how-to-use-them-131b863785f/
https://imagej.net/Git_Conflicts
https://njit2.mrooms.net/pluginfile.php/1107711/mod_resource/content/1/GitHub.pdf
