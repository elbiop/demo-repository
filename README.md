# demo-repository
It is from git training course: git and GitHub for beginners from FreeCodeCamp
start date: 11/17/2022

the extension of README.md stands for markdown
<p>
# git commands:
<ul>
    <li><pre>init  : converts a directory into a new repository
            $ git init</pre></li>
    <li><pre>remote: Establish a connection between unconnected emote and local repositories
        it is used when local and remote repositories are created separately intead of being clones of one another
        $ git remote add master "git@github.com:example/remote-repository.git</pre></li>
    <li><pre>clone : brings a repository hosted online to local computer
            $ git clone github.com:elbiop/demo-repo.git</pre></li>
    <li><pre>add   : begin to track a file in git that isn't being tracked
            $ git add filename.ext
            $ git add . # reack all files</pre></li>
    <li><pre>commit: save your files changes in git
            $ git commit -m "Reasosn for the changes or descriprion"</pre></li>
    <li><pre>push  : upload changes to the remote repository
            $ git push origin master
            in order to avoid writing "origin master" a default upstream option ( -u ) can be set
            $ git push -u origin master
            int the subsequent pushes only "$ git push" will need to be written</pre></li>           
    <li><pre>pull  : download changes from remote repo to local machine</pre></li>
    <li><pre>status: gives information about untracked changes</pre></li>
    <li><pre>gitignore: specifies which files should't be tracked</pre></li>
    <li><pre></pre></li>
</p>
# Establishing connection with git-hub  
To establish comunination between GitHub and your local repository trugh git
you neeed to download git credential manager

# branching
A branch is a tracking workflow preceding the main or "master" branch
The workflow is the same for each branch but no branch can see the changes done to the other branches
