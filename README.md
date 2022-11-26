# demo-repository
It is from git training course: git and GitHub for beginners from FreeCodeCamp
start date: 11/17/2022

the extension of README.md stands for markdown

git commands:
    clone : brings a repository hosted online to local computer
            $ git clone github.com:elbiop/demo-repo.git
    add   : begin to track a file in git that isn't being tracked
            $ git add filename.ext
            $ git add . # reack all files
    commit: save your files changes in git
            $ git commit -m "Reasosn for the changes or descriprion"
    push  : upload changes to the remote repository
            $ git push origin master           
    pull  : download changes from remote repo to local machine
    status: gives information about untracked changes
    
    gitignore: specifies which files should't be tracked
  
# Establishing connection with git-hub  
To establish comunination between GitHub and your local repository trugh git
you neeed to generate a key using ssh-keygen:
ssh-keygen + tipe of encription + strength of encription + email

$ ssh-keygen -t rsa -b 4096 -C "email@example.com"

The default for the key file is:/c/Users/USERNAME/.ssh/id_rsa
enter a key password.
after that two files were created in the .ssh directory:
    id_rsa (private key), id_rsa.pub(public key)

$ cat C://Users//USERNAME//.ssh//id_rsa.pub

the output should look like this:
    ssh-rsa AAAAB3NzaC1yc2EAAAADAQA.......
    .......AAAAB3NzaC1yc2EAAAADAQAn.......
    .......by6xqw== email@example.com
    
copy the output code then go to GitHub on user account, settings,
 ssh and GPG keys, and paste it

$ eval "$(ssh-agent -s)"