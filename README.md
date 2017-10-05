# Airbnb Machine Learning Workshop Repository #

This repository contains the files and source code for the Ruby Unconference 2017 Airbnb Workshop, follow the steps for the configuration of
the python environment and use the interactive jupyter notebooks to review the workshop.

### Setup ###

* Summary: To execute the Jupyter notebooks we need to install a python distribution with all the necessary packages (e.g. IPython, Numpy, Scikit-Learn). There is a distribution that already has this packages, so we need to install it. For intructions about the installation visit [Anaconda](https://docs.anaconda.com/anaconda/install/).

## Setting your python environment

# (option 1) Using Anaconda

- Install anaconda according to the instructions.
- [Optional] Run ```pip install -r anaconda-requirements.txt``` to install the packages requirements manually.
- Download the dataset from insideairbnb ([link](http://data.insideairbnb.com/united-kingdom/england/london/2017-03-04/data/listings.csv.gz)) to the __data__ directory.
- Extract the downloaded gunzip files in the data directory: ```gunzip *.zip```
- Run the Jupyter notebook inside the notebooks directory: ```jupyter-notebook notebooks/ML_Workshop.ipynb --ip=YOUR_IP --port=AVAILABLE_PORT```
- If you are going to run the notebook from a different device in the same network, use the url generated after running the ```jupyter notebook list``` at the terminal. That should display an url (e.g http://IP_ADDRESS:PORT/?token=xxxxxxxxxxxxxxxxxxxxxxx). Now you can access the notebook from your browser selecting the available notebook that you need.
- If you wish to use the dark Jupyter notebook theme (possibly a bit better for your eyes) run the following command: ```jt -t chesterish -T```
- If you wish to go use the dark Jupyter notebook theme (possibly a bit better for your eyes) run the following command: ```jt -r```

# (option 2) Using pyenv and virtualenv

- [Install pyenv](https://github.com/pyenv/pyenv)
- Install Python version 2.7.13 using pyenv ```pyenv install 2.7.13```
- Install virtualenv ```pip install virtualenv```
- Create an virtualenv environment in the project folder ```virtualenv .```
- Activate the virtualenv environment in the project folder ```source bin/activate```
- Upon activation, run ```pip install -r requirements.txt``` to install the dependencies in the virtual environment


## Dependencies used

- Python 2.7.13
- jupyter ~=1.0.0
- jupyterthemes ~=0.18.0
- numpy ~=1.12.1
- pandas ~=0.20.1
- scikit-learn ~=0.18.1
- seaborn ~=0.8

### Who do I talk to? ###

* Mail to: jairo.diaz |at| codescrum.com, miguel.diaz |at| codescrum.com or milton.arango |at| codescrum.com
* By Codescrum

# Contributors
* * *
* [Milton Arango G](https://bitbucket.org/marangog/)
* [Miguel Diaz](https://bitbucket.org/gato_omega/)
