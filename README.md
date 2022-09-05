### Steps

#### TO clone Github repository in your local system
1) Copy clone link from github for required repository
2) Go To "Terminal" navigate to location where you want to clone repository
> pwd: Present working directory
> cd: Change directory
> ls: List files in that location
3) After going to location type below command
> git clone copied_URL

#### To create new enviroement 
For each roject create new enviroement in conda
1) First deactivate existing enviroement using below command in powershell
> deactivate
2) To create new enviroement in command prompt
> conda create -p venv python==3.7 -y
3) To activate newly created enviroement in command prompt
> conda activate venv
4) To install required libraries in new envoriment follow below step
> Create requirements.txt file which has all the required libraries name
> pip install -r requirements.txt in command prompt

#### To commit changes to git repository
1) TO set user name in loacl system
> git config --global user.name "Nikhil" in command prompt
2) To set email id of git in local system
> git config --global user.email "nikhilv2411@gmail.com" in command prompt
3) command to add file to git repository
> git add <file_name> # To add specific file
> git add . # To add all the files in that location 
4) To see ststus of git
> git status
5) To commit files
> git commit -m "Commit message"
6) To push files to git repository
> git push origin main

#### To create requirment file
> pipreqs
