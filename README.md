# bash
github.com commands
git config --list
git config --global user.username yourgithubusername
git config --global user.name yourgithubusername
git config --global user.user yourgithubusername
git config --global user.email yourgithubemail@mail.ioe
git config --list

After creating a config file (~/.ssh/config) it worked. This is what I had to put in it:

Host github.com
User git
Port 22
Hostname github.com
IdentityFile ~/.ssh/id_rsa
TCPKeepAlive yes
IdentitiesOnly yes


https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent


git remote set-url origin git@github.com:icebowl/bash.git


trail 1
trial 2
trial 3
trial 4
trial 5
trial 6
trial 7
trial 8
trial 9
