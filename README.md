


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
#nbb: this will analyise all .py files in curr dir and subdirs
flake8 --statistics

#checks compliance with PEP 8
https://www.python.org/dev/peps/pep-0008/

https://docs.pytest.org/en/latest/
pytest will run all files of the form test_*.py or *_test.py in the current directory and its subdirectories.
https://docs.pytest.org/en/latest/goodpractices.html#test-discovery



https://circleci.com/
