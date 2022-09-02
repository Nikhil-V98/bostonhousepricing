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
> pip install -r requirements.txt