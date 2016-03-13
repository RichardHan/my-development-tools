I'm Richard Han and I'm Full Stack Developer.

Here I will publish development tools, which I use or intend to use.


## Windows environment

1. [Git client] SmartGit - http://www.syntevo.com/smartgit/

2. [Editor] ATOM - https://atom.io/

3. [Editor] Sublime Text 3 - https://www.sublimetext.com/3



4. [Visual diff and merge tool] Meld - http://meldmerge.org/

5. [MongoDB management tool] Robomongo - http://app.robomongo.org/download.html

6. [IDE] Visual Studio 2015 Enterprise

7. [IDE Extension] - Web Essentials 2015 for Visual Studio - http://vswebessentials.com/download

8. [console emulator] - Cmder - http://cmder.net/

## Linux(Ubuntu 15.10) environment

1. [Git client] SmartGit - http://www.syntevo.com/smartgit/

2. [Editor] ATOM - https://atom.io/

3. [Editor] Sublime Text 3 - https://www.sublimetext.com/3

4. [Visual diff and merge tool] Meld - http://meldmerge.org/

5. [MongoDB management tool] Robomongo - http://app.robomongo.org/download.html


## Linux(Ubuntu) command install memo
```
  # node js v4
  curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash -
  sudo apt-get install -y nodejs
 ```

## Sublime 3 Package Installed
 ```
 #
 # [Install Package Control] - https://packagecontrol.io/installation
 #
 # Emmet - https://github.com/sergeche/emmet-sublime
 # SideBarEnhancements - https://packagecontrol.io/packages/SideBarEnhancements
 # Bracket​Highlighter
 # SublimeCodeIntel
 # HTML5
 # Sublime​Linter - https://packagecontrol.io/packages/SublimeLinter
 # Live​Style - http://livestyle.io/
 # HTML-CSS-JS Prettify [CTRL + SHIFT + H]
 # Git
 # Doc​Blockr - https://packagecontrol.io/packages/DocBlockr
 # SideBarGit
 # Theme - Soda - https://packagecontrol.io/packages/Theme%20-%20Soda
 # Markdown Preview
 # ReactJS
 # JSX
 # Babel 
 # SCSS
 
 ```
 

## Docker Install
 ```
 sudo apt-get update
 sudo apt-get install apt-transport-https ca-certificates
 sudo apt-key adv --keyserver hkp://p80.pool.sks-keyservers.net:80 --recv-keys 58118E89F3A912897C070ADBF76221572C52609D
 sudo sh 
 
 # ACTION: update /etc/apt/sources.list.d/docker.list => deb https://apt.dockerproject.org/repo ubuntu-wily main
 vi /etc/apt/sources.list.d/docker.list
 # deb https://apt.dockerproject.org/repo ubuntu-wily main
 
 sudo apt-get update
 sudo apt-get purge lxc-docker
 apt-cache policy docker-engine
 sudo apt-get update
 sudo apt-get install linux-image-extra-$(uname -r)
 sudo apt-get update
 sudo apt-get install docker-engine
 sudo service docker start
 sudo docker run hello-world
 
 sudo usermod -aG docker $(whoami)

 # ACTION: logout & login
 
 sudo -i
 curl -L https://github.com/docker/compose/releases/download/1.6.2/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
 chmod +x /usr/local/bin/docker-compose
 exit
 docker-compose --version
 
 ```
