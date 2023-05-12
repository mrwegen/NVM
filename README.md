# NVM
NVM and Node.js Cheat code
//How to install NVM in to linux Machine 
-apt update && upgrade 
-- apt install curl 
--curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
-~/.nvm
-export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm

--nvm install latest
//To get the complete version list //
--nvm ls-remote

--nvm install (version no)
How to check installed node js version .
-nvm ls
//Switch to another version
To switch to another version for the active shell use nvm use.
--nvm use (version no)
//Switch to the latest installed version:

-nvm use node
//Use the latest LTS version:

--nvm use --lts

