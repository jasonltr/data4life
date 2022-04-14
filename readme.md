## Running the script ##  
If using jupyter notebook IDE, all functions can be ran sequentially and in blocks  
If using python3 interpreter in CLI, run `exec(open("<filepath>").read())`  

### Install gh cli ###  
[installing gh cli](https://github.com/cli/cli/blob/trunk/docs/install_linux.md)  
`curl -fsSL https://cli.github.com/packages/githubcli-archive-keyring.gpg | sudo dd of=/usr/share/keyrings/githubcli-archive-keyring.gpg`  
`echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/githubcli-archive-keyring.gpg] https://cli.github.com/packages stable main" | sudo tee /etc/apt/sources.list.d/github-cli.list > /dev/null`  
`sudo apt update`  
`sudo apt install gh`  

### Created github repo ###  
`gh auth login`  
`gh repo create data4life --public --source '<filepath>'`  

### Push initial commit into github ###  
`git remote add origin https://github.com/jasonltr/data4life.git`  
`git branch -M main`  
`git push -u origin main`  

## placeholder ##



