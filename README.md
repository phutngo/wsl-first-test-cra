# GETTING STARTED
This repo was set up using cra within wsl ubuntu. To setup a similar project from scratch follow these steps:

1. Open Ubuntu Bash
2. cd // home/phungo 
3. cd _PROJECTS
4. npx create-react-app my-app
5. cd my-app
6. code .

Now I'm inside VSCode with WSL Remote.
Create a local git - by going to Source Control side panel
Create and hook it up to remote Github 

"…or push an existing repository from the command line

git remote add origin https://github.com/phutngo/wsl-first-test-cra.git
git branch -M main
git push -u origin main
"
------------------------------------------------------------------
https://code.visualstudio.com/docs/remote/wsl#_getting-started

------------------------------------------------------------------

http://manpages.ubuntu.com/manpages/bionic/man8/apt.8.html
sudo apt full-upgrade to update packages on ubuntu

TODO later if using both wsl and windows for 1 repo
https://code.visualstudio.com/docs/remote/troubleshooting#_resolving-git-line-ending-issues-in-wsl-resulting-in-many-modified-files


# Install nvm, node.js and npm on WSL
https://docs.microsoft.com/en-us/windows/dev-environment/javascript/nodejs-on-wsl#install-nvm-nodejs-and-npm

nvm ls //see which node versions i have installed

# Git
We recommend adding a .gitignore file to your projects. GitHub offers a collection of useful .gitignore templates with recommended .gitignore file setups organized according to your use-case. For example, here is GitHub's default gitignore template for a Node.js project.

If you choose to create a new repo using the GitHub website, there are check boxes available to initialize your repo with a README file, .gitignore file set up for your specific project type, and options to add a license if you need one.

https://docs.github.com/en/get-started/getting-started-with-git/configuring-git-to-handle-line-endings#per-repository-settings