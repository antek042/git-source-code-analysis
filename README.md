This repository is for learning purposes to make me understand better the internals of git with feymann learning method.
Also I wish that it can help some newcomers like me to easier the dive in process.

Steps to get the first commit of git source code:
 - clone the repo from github:
 ```bash
    git clone https://github.com/git/git.git
 ```
 - switch to the first commit:
 ```bash
    git switch --detach e83c5163
 ```
 - open the project in your favourite editor

Thats it now you are ready to analise the git first commit source code.

My analises for each source or header file will be in files named exactly like originals but it will ends with *.md*.