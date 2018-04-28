* https://realpython.com/python-git-github-intro/
* http://nvie.com/posts/a-successful-git-branching-model/
* https://gist.github.com/blackfalcon/8428401
* 
Keeping your #Github fork is very important especially when the original source changes stuff often (like me! ☺️)

Here are three very simple steps to keep your forked git up2date

Step #1: Clone your fork to your desktop

git clone git@github.com:YOUR-USERNAME/YOUR-FORKED-REPO.git

Step #2:: Add remote from original repository in your forked repository: do the following three steps

cd into/cloned/your_fork-repo
git remote add upstream git://github.com/ORIGINAL-REPO.git
git fetch upstream

Step #3:: Updating your fork from original repo to keep up with their changes:

git pull upstream master

That's it. 
