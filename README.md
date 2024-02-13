# JPMC Task 2
Starter repo for task 2 of JPMC's Forage program


## Steps to create local environment
python3 -m pip --version  
python3 -m pip install --upgrade pip  
pip3 install python-dateutil  

## run servers3.py in root
python3 datafeed/server3.py

## create a git patch with multiple N commits
git format-patch -N –stdout > multi_commit.patch  
N is the number of total commit  