These assignments are using jupyter notebook, these allow for both code and text anwsers in the same documents. 
For submission we only want the jypyter file (.ipynb).


To run this assignment you need:

python3 (python >= 3.7, I run 3.10)

jupyter notebook
https://jupyter.org/

It is also possible to install jupyter notebook as an extension in vstudio or pycharm if you rather want to use thoes. 


python3
All dependencies can be installed using pip (if you have both python2 and python3 installed use pip3).

numpy
https://pypi.org/project/numpy/
scipy
https://pypi.org/project/scipy/
pygame (used for rendering and visuallization)
https://pypi.org/project/pygame/
(Note for those using conda instead of pip, the pygame is not up to date with conda and might cause problems).

If that pygame version does not exist for newer python versions, then this should work instead (community version)
pip install pygame-ce

The only file that should be modified is ps1.ipynb

Creating a virtual environment
# cd into local project
# Create the environment folder named 'env'
python3 -m venv env

# Activate it (you will see '(env)' appear at the start of your terminal prompt)
source env/bin/activate
