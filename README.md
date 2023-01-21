create env

''' bash
conda create -n wineq python=3.7 -y

'''
 activate env

 ''' bash

 pip install -r requirements.txt
 ,,,

 git init

 dvc init

 dvc add data_given/winequality.csv

 git add .
 git commit -m "Creating commit"

or 

git add . && git commit -m "Creating commit"

 git remote add origin https://github.com/Karthikeyan-Ravichandran22/MLOps-WineProject.git

 git branch -M main

 git push origin main

 # stage 1 complete