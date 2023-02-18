- `echo <inputMessage>` - Simply takes its arguments and echoes them to the terminal
- `pwd` - Print the working directory
- `ls <path>` - List [[path]] contents 
	- `-a` - Show all hidden files and directories.
- `cd <path>` - Change working directory
- `mkdir <path>` - Create a new directory
- `touch <path>` - Create a new empty file
	- "touch" existing files could update their modification time.
- `mv <soursePath> <targetPath>` - Move files or directories to new locations
- `cp [-r] <sourcePath> <targetPath>` - Copy files or directories to new locations
	- `-r` allows users to copy directories and their contents
- `rm [r] <path>` - Remove files and directories
	- `-r` allows users to copy directories and their contents
- `man [section] <program>` - Get very detailed syntax for a particular program.
	- All CLI programs can be found in Section 1.
## Git Cloning Tutorial
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
### 2. Create Github vault by https/git
```shell
git init
touch README.md
git add README.md
git commit -m "first commit"
git remote add origin <HTTPS/SSH>
git push -u origin master
```

​	
