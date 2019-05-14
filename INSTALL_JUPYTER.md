# How to install Jupyter notebook


## Users who do not have Python or do not use Python regularly

**Installing jupyter notebook by installing anaconda**

Anaconda is a free and open-source distribution of the Python and R programming languages for scientific computing 
(data science, machine learning applications, large-scale data processing, predictive analytics, etc.), that aims to 
simplify package management and deployment 
[WikipediA](https://en.wikipedia.org/wiki/Anaconda_(Python_distribution))

Installation of anaconda is simple. Visit the 
[Anaconda distribution](https://www.anaconda.com/distribution/#download-section)
website. Then download and run the installation package for your operating system (***You may need admin privileges***). 

*If you are unfamiliar with Python, it is recommended to install the Python3 Anaconda distribution*

A significant advantage of installing Anaconda is that it will automatically configure your computer to use the Anaconda
 distribution of Python. ***Therefore, if you are a regular Python user you may not want to install Anaconda***. 

## Users who have Python and use Python regularly

**Installing jupyter notebook using pip**

*Optional, create a virtual environment and activate*

Open a terminal or command prompt

Type:

pip install --upgrade pip
pip install jupyter

***Jupyter notebooks will run on Python2 but Python2 will no longer be supported from early 2020.*** It is therefore 
recommended to upgrade your Python distribution. 

If you want to continue to use Python2, consider installing Anaconda Python3 distribution and creating a Python2 virtual
 environment.

Once you have installed Anaconda, open a terminal or command prompt and type:

conda create -n python2
conda activate python2

*When you have finished working, deactivate your environment by typing*

conda deactivate


## Running jupyter notebook
*If you have installed jupyter in a Python environment, remember to activate it. To view your environments, type conda 
info --envs*

On the terminal or command prompt type:

Jupyter notebook

The program will open a web browser displaying your home directory

Create a new directory for your jupyter notebook files

Start playing!

When you are finished, hold <control and c> to deactivate jupyter


## Documentation

**Anaconda documentation**
[docs >> conda](https://docs.conda.io/en/latest/)
 
**Jupyter notebook documentation**
[docs >> conda](https://docs.conda.io/en/latest/)
 
