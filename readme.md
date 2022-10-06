  create env
  
  '''bash
  conda create -n wineq python=3.7 anaconda

  activate

  conda activate wineq
 
  created a req file

  installed the req
  '''bash
  pip install -r requirements.txt

  download data from kaggle
  '''
  '''bash
  git init

  dvc init

  dvc add data_given/winequality.csv

  git add .

  git commit -m "first commit"

  git remote add origin https://github.com/Prakhar2295/simple-dvc-demo.git
  
  git branch -M main
  
  
  git add . && git commit -m "Update Readme.md "
  
  git remote add origin https://github.com/Prakhar2295/simple-dvc-demo.git
  
  git fetch origin main:tmp
  
  git rebase tmp
  
  git push origin HEAD:main
  
  git branch -D tmp


  