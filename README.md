# generate-changelog
Script to automatically tag version and generate change log which includes version numbers and their commits

## Installation

You can **copy the script inside your repo** and run it when your release it ready. The script will automatically:
 - Tag your latest commit with appropriate version number, 
 - Generate a CHANGES file which will include all your commits for the current release and will append to it if already exists.
 - Generate VERSION file which will contain the current version
 
 **How to execute the script?**
 
 Just ensure the script is executable by running following command inside your repo.
 
 `chmod +x ./generate-changelog.sh`
 
 then 
 
 `./generate-changelog.sh`
 
 Easy! isn't it? Have fun!