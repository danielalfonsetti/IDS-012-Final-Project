# IDS-012 Final Project


## Setting Up

Install this repo via

```bash
git clone https://github.com/danielalfonsetti/IDS-012-Final-Project.git
```

After cloning, cd into the directory. 
```bash 
cd IDS-012-Final-Project
```

## Installing Python Requirements + Python Virtual Environments

Currently using Python 3.9.2.
The python requirements for this project be found in `requirements.txt`.  

----
(Optional) You may want to create your own local python virtual environment for this project, so that python package installations downloaded for this project are only used in this project. To create the new environment and then activate it use

```bash
python3 -m venv venv 
source ./venv/bin/activate
```
-----

To install all of the dependencies in the current environment, you can run the 
following in a command line (again, you may want to create a virtual environment).

```bash
$ pip install -r requirements.txt
```

NOTE: If you are using a Mac, it is probably necessary to call `pip3` instead of `pip`

## Ideal Workflow

After cloning this repo onto your computer, make a branch for your edits.
Once you have finished making edits, merge the remote master back into your local branch before
you push your local branch to the remote repo. Then submit a pull request.

The pull request should be able to automatically merge into master since you just merged master into your 
current branch.

If you changed someone else's file, ideally you should request a review before you merge.

If you are adding to requirements.txt using `pip freeze > requirements.txt`, please make sure you are using virtual environments so that requirements.txt does not get overwhelmed with superfluous packages from
other python packages you have on your computer that may not be used in this project. 
See: \
https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/ or \
https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

## Directory Sturcture

`misc`: Feel free to put experiments/in-progress code in , and once they are ready enough, move them to `scripts`. \
`scripts`: Code that is 'ready enough' \
`plots`:  Graphics that should go into the 6-8 page paper and/or the presentation board. \
`data`: The data being analyzed.

