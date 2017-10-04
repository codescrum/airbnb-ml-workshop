# Airbnb Machine Learning Workshop Repository #

This repository contains the files and source code for the Ruby Unconference Airbnb Workshop, follow the steps for the configuration of
the python environment and use the interactive jupyter notebooks to review the workshop.

### Introduction ###

* Quick summary
* Set up
* Contributors

### Set Up ###

* Summary: To execute the Jupyter notebooks we need to install a python distribution with all the necessary packages (e.g. IPython, Numpy, Scikit-Learn). There is a distribution that already has this packages, so we need to install it. For intructions about the installation visit [Anaconda](https://docs.anaconda.com/anaconda/install/).

## Setup

# Using Anaconda

- Install anaconda according to the instructions.
- [Optional] Run ```pip install -r anaconda-requirements.txt``` to install the packages requirements manually.
- Download the datasets from google drive ([link](https://drive.google.com/open?id=0B-LN0hetu-kcWExqV29IbkJ5TlU)) to the __data__ directory.
- Extract the downloaded zip files in the same directory: ```unzip *.zip```
- Run the Jupyter notebook inside the notebooks directory: ```jupyter-notebook notebooks/ClickMechanic_LabourTimes.ipynb --ip=YOUR_IP --port=AVAILABLE_PORT```
- If you are going to run the notebook from a different device in the same network, use the url generated after running the ```jupyter notebook list``` at the terminal. That should display an url (e.g http://IP_ADDRESS:PORT/?token=xxxxxxxxxxxxxxxxxxxxxxx). Now you can access the notebook from your browser selecting the available notebook that you need.
- If you wish to use the dark Jupyter notebook theme (possibly a bit better for your eyes) run the following command: ```jt -t chesterish -T```
- If you wish to go use the dark Jupyter notebook theme (possibly a bit better for your eyes) run the following command: ```jt -r```

# Using pyenv and virtualenv

- [Install pyenv](https://github.com/pyenv/pyenv)
- Install Python version 2.7.13 using pyenv
- Install virtualenv ```pip3 install virtualenv```
- Create an virtualenv environment in the project folder ```virtualenv .```
- Activate the virtualenv environment in the project folder ```source bin/activate```
- Upon activation, run ```pip install -r requirements.txt``` to install the dependencies in the virtual environment


## Dependencies:
- Python ~2.7
- Numpy
- SciPy
- LightGBM
- Matplotlib
- Pandas
- Scikit-Learn
- Seaborn

### Who do I talk to? ###

* Mail to: miguel.diaz@codescrum.com or milton.arango@codescrum.com
* By Codescrum

# Contributors
* * *
* [Milton Arango G](https://bitbucket.org/marangog/)
* [Miguel Diaz](https://bitbucket.org/gato_omega/)
