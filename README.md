
# Future Rockstars

## Development Progress

All development can be tracked on our public Trello board, which is located [here](https://trello.com/b/sDJQagZ3/future-rockstars-python-project).

## Installation

### Pre-requisites

[Python 3.6.x](https://www.python.org/downloads/) - Python 3.6.x is required to work
with this project, so please feel free to download the appropriate installer for your operating system. This will install Python and Pip, Python's package manager. 

virtualenv/pyvenv - We use this to create virtual environments in which to develop Python applications. Doing this allows us to install packages only for the specific project we are working on instead of globally. This can be installed
by running the following command in Command Prompt or a terminal: 

- `pip install virtualenv`

Now that those are both installed, we can move on to getting the application and environment setup

### Application

First, we will want to clone this repository to our local machines. To do this, simply navigate to a directory that you store other projects in and run the following command in Command Prompt or a terminal: 

- `git@github.com:thehouseplant/future-rockstars.git`

Now, enter `cd future-rockstars` and then run the following commands to get a Python 3.6 environment configured to run the application in:

- `pyvenv-3.6 env`

- `source env/bin/activate`

Now, when you look at your Command Prompt or terminal and you should see `(env)` in the prompt. This means that the Python environment has been activated and you can begin
installing dependencies for the project. For our purposes, all of our dependencies are stored in the `requirements.txt` file and can be installed by running the following: 

- `pip install -r requirements.txt`

You now have all of the application code, Python environment, and application package dependencies installed. To make sure that the application is working, run the following command:

- `python app.py`

This will start the server and the application will be viewable at [http://localhost:5000](http://localhost:5000).

## Contribution Guide

Coming soon...