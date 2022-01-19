# VS Code Devcontainer for OS

* Windows 11 does not support Virtualbox, so this is a work around
* Basic setup needed for compile xv6 in a container, so your computer does not install a bunch of stuff
* When done, simply delete the container and image, and everything is removed
  
## How to use

1. Install Docker and necessray dependancies (WSL) to your computer
2. Install VS Code and add Remote-Container extension
3. Install Git for pulling and pushing code to Github
4. Open this folder in VS Code and clone the assignment here
5. Open VS Code Menu, or press ctrl+shift+p, and select "Remote-containers: rebuild and reopen in container"
   1. Make sure Docker is running at this point
6. Wait for installations, and you should be connected to the dev container
7. Edit your assignment, and compile your code
8. To exit container, open VS Code Menu, or press ctrl+shift+p, and select "Remote-containers: open locally"
9. Remember to commit your local changes to Github
