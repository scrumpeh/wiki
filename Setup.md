Instructions for setting up an environment

0. Generate ssh keys
Open terminal
Type ssh-keygen -t rsa -b 4096
Say yes to all prompts
Type cat ~/.ssh/id_rsa.pub
Copy ALL of the output into Github
Go to Github -> settings -> ssh keys -> add key. Paste the output and save the key

1. Pulling dotfiles from Github
Make a (temporary) directory called dotfiles
Go to dotfiles repo in Github and copy the ssh clone link
In terminal in the dotfiles directory, type git clone <link> .
Move everything in the dotfiles directory in my computer into my home directory (i.e. into ~) - type mv .git ~
Type cd ~/ 
Type git reset --hard master

2. Install vundle
Search for vundle on github, follow quick start instructions (just clone with git)
Open vim and type :BundleInstall
Restart vim using :qa!

3. Install inconsolata
In terminal, type sudo yum install inconsolata




