#Git References


Git Workflows with Git Commands


GitHub has over 100 million repositories. You can clone a repository and sync changes back to the original. You can also fork a repository and use it as the base for the new project or work on that project independently.

The steps included in a GitHub workflow are:

Clone the remote repository or initialize a Git repository.

Move files to a staging area.

Perform an initial commit.

Create a branch and work on it.

Add files to the staging area and commit.

Push local commits to the remote repository.

Create a pull request for review and merging.

Use the pull operation to update the local repository.

Multiple roles are involved in managing a project: Developer, Integrator, and Repository Administrator.

A Developer working in a group project uses commands like git clone, git pull, git fetch, git push, and git request-pull in addition to the ones needed by a standalone developer.

An Integrator in a group project reviews and integrates changes made by others. Integrators use commands like git pull, git revert, and git push in addition to the ones needed by participants.

Repository Administrators structure how the repository is organized and how users interact with the repository. They also configure the servers needed for accessing the web services and documentation, define email and index settings, and manage the look and feel of the application.

The following table shows various Git commands:

git init

git checkout

git revert

git-format-patch

git fetch upstream

git status

git merge

git config --global user.email

git-request-pull

git merge upstream/main

git add .

git clone

git config --global user.name

git-send-email

git pull upstream

git commit 

git pull

git remote -v

git-am

git web

git log

git push

git remote rename

git-daemon

git-instaweb

git reset

git version

git remote add origin

git remote -v

git-pull downstream

git branch

git diff

git-remote

git remote add upstream

git-rerere


Glossary: Git Commands and Managing GitHub Projects
Welcome! This alphabetized glossary contains many of the terms in this area. This comprehensive glossary also includes additional industry-recognized terms not used in course videos. These terms are essential for you to recognize when working in the industry, participating in user groups, and in other professional certificate programs.

Term	                                                                  Definition

Cloning                    	                        A process of creating a copy of the project's code and its complete version history from the remote repository on the local machine.
Commit	                                            A snapshot of the project's current state at a specific point in time, along with a description of the changes made.
Developer                                           A computer programmer who is responsible for writing code.
Distributed version control system (DVCS)	          A system that keeps track of changes to code, regardless of where it is stored. Multiple users work on the same codebase or repository, mirroring the codebase on their computers if needed, while the distributed     
                                                    version control software helps manage synchronization amongst the various codebase mirrors.
Fork	                                              A copy of a repository into your GitHub account.
Forking	                                            Forking creates a copy of a repository on which one can work without affecting the original repository.
GitHub	                                            A web-hosted service for the Git repository.
Git	                                                A free and open-source software distributed under the GNU General Public License. 
                                                    It is a distributed version control system that allows users to have a copy of their own project on their computer anywhere in the world.
Integrator	                                        A role that is responsible for managing changes made by developers.
Master branch	                                      A branch that stores the deployable version of your code. The master branch is created by default and is definitive.
Merge	                                              A process to combine changes from one branch to another, typically merging a feature branch into the main branch.
Origin	                                            A term that refers to the repository where a copy is cloned from.
Pull request	                                      A process used to request that someone review and approve your changes before they become final.
Remote repositories	                                Repositories that are stored elsewhere. They can exist on the internet, on your network, or on your local computer.
Repository administrator	                          A role that is responsible for configuring and maintaining access to the repository.
Repository	                                        A data structure for storing documents, including application source code. It contains the project folders that are set up for version control.
Staging area	                                      An area where commits can be formatted and reviewed before completing the commit.
Upstream	                                          A term used by developers to refer to the original source where the local copy was cloned from.
Version control	                                    A system that allows you to keep track of changes to your documents. This process allows you to recover older versions of the documents if any mistakes are made.
