# command_set


check if yolov8 install successfully. 

import ultralytics

ultralytics.checks()


pip install notebook

jupyter notebook


Here are some essential commands to kick-start your GitHub journey!
1. git clone: Clone a repository to your local machine.
git clone <repository_url>`: Copy a repository from GitHub to your local machine
2. git add: Stage changes for commit.
git add <file>`: Stage changes for commit.
3. git commit: Commit staged changes.
git commit -m "Commit message"`: Commit staged changes with a descriptive message.
4. git push: Push committed changes to a remote repository.
git push origin <branch_name>`: Push commits to a specific branch on GitHub.
5. git pull: Fetch and merge changes from the remote repository.
6. git branch: Create, list, or delete branches.
git branch <branch_name>`: Create a new branch.
7. git checkout: Switch between branches or restore files.
git checkout <branch_name>`: Switch to a different branch.
8. git merge: Merge changes from one branch into another.
git merge <branch_name>`: Merge changes from one branch into the current branch.
9. git status: View the status of files in the repository.
10. git log: View commit history.



systemctl --user start docker-desktop (or just click the icon)

systemctl --user stop docker-desktop

To enable Docker Desktop to start on sign in, from the Docker menu, select Settings > General > Start Docker Desktop when you sign in to your computer.

Alternatively, open a terminal and run:
 systemctl --user enable docker-desktop


anaconda-navigator # run it under the default base env



docker build -t welcome-to-docker .
The -t flag tags your image with a name. (welcome-to-docker in this case). And the . lets Docker know where it can find the Dockerfile.
