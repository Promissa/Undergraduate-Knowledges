## Setup
### 1. Set up SSH public key (Optional)
``` shell
# Create SSH content
cd ~
mkdir .ssh
cd .ssh
ssh-keygen -t rsa
# Add SSH key to the ssh-agent
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/<keyname>
```
### 2. Create a Github Vault on Github or Gitee
### 3. Setup local .git config
```shell
git init
touch README.md
git add README.md
git commit -m "first commit"
git remote add origin <HTTPS/SSH>
```
*If you want to push your files to the default `main` branch:*
``` shell
git branch -M main
git push -u origin main
```
*Or if you don't want:*
``` Shell
git push -u origin master
```

## Push
```Shell
git add -A
git commit -m "whatever you want"
git 
```
