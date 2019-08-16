


#useful git update and ignore sequence
#update .gitignore to exclude files from repo
git rm -r --cached .
git add .
git commit -m ".gitignore fix"
git push


source:
https://realpython.com/python-continuous-integration/

pip install --upgrade virtualenv
virtualenv --version  
doskey /history



virtualenv calculator
#NB in windows
calculator\Scripts\activate
#create prompt > (calculator) \path\to\curr\dir

#create dir for git repo CalculatorLibrary & cd 
#create calculator.py
git add, commit, push

pip install flake8 pytest pytest-cov
#to see list of packages required.
pip freeze
#now create requirements.txt for git repo
pip freeze > requirements.txt

#if this is run in dir where calculator is a subdir then slow.
flake8 --statistics

https://circleci.com/
