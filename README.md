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