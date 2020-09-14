# Python for Climate Physics  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AJueling/python_climate_physics.git/master)
This is a collection of jypyter notebooks for an introductory workshop series on python for the Climate Physics master programme at the Institute for Marine and Atmospheric research Utrecht (IMAU), Utrecht University, held in September/October 2020.

_To interact with the notebooks you can launch a binder instance by clicking the binder link button in the heading. This can take a short while to initialize. Also beware that it will shut down after 10 minutes of inactivity (and all changed contents will be lost)._

## Purpose
We noticed in the last years that the programming background of everyone varies with some having zero experience and others having quite a lot already.
In addition, there are common specificities in working with (geo-) scientific data which you could all discover by yourselves, but why reinvent the wheel!?

## Workshop structure
There are four workshops.
The first two cover the basics of programming in python and if you feel comfortable with simple programming and plotting you will probably know this already and won’t want to attend.
The second two workshops focus on packages specific to our field and best practices for computational research projects.
I would thus recommend that all of you at least look at the contents of the last two workshops.
Below there is a list of resources that are worth checking out.

We meet Mondays during the after lunch time slot.
I will be there from 13:00 for those who need help with their installations.
The official workshop time is 13:15-15:00.

This is the current course outline:
1. [14.9.20 13:15-15:00] basic programming in python: data types, lists, dictionaries, loops, conditionals, functions, basic unix commands
2. [21.9.20 13:15-15:00] common python packages and basic plotting: numpy, matplotlib, scipy
3. [28.9.20 13:15-15:00] working with geoscientic data: netcdf data format, pandas, xarray
4. [5.10.20 13:15-15:00] mapping with cartopy, open science, and best practices
(There is a chance I will shift the last two workshops by a week.)

I will use jupyter notebooks for teaching because they can combine high quality documentation, code and output. For you to participate in the workshops you need to have a way to execute them. Please install Anaconda/Miniconda before the first workshop (see instruction below)!

The workshops are held online in MS Teams.
You can join the team `Python for Climate Physics` with the code I shared by email.
I will shortly introduce the content lecture-style, but most of the time is reserved for exercises and questions that may arise.
This is the first time I teach online, so things may change and even more than in normal times, I would like your feedback!
I will make the workshop materials available in advance, also so that you can decide whether there is anything new to you.
I will sent one more email before the first workshop, the rest of the communication will be via Teams.


---
## Python/Jupyter installation instructions:

For coherence, I strongly recommend we all use a python installation with the conda package manager.
You have two (equally valid) options:
1. Anaconda: https://docs.anaconda.com/anaconda/install/ or 
2. Miniconda:  https://docs.conda.io/en/latest/miniconda.html
The difference between them is that Anaconda includes many packages (including some you will never use) and consequently uses up quite some disk space.
It features a graphical user interface. Miniconda, on the other hand, only includes the bare necessities and packages need to installed as they are needed, thus using a lot less disk space. 

Once you have installed one of the two condas, there are two ways to work with jupyter notebooks:
1. jupyter notebook app: the basic, but sufficient option
2. jupyter lab app: the more advanced option
With Anaconda you can choose either app from the graphical user interface.
With Miniconda you need to install jupyter first.
You can do this by running `conda install jupyter jupyterlab` and subsequently confirming.
Then you can type in the terminal `jupyter notebook` or `jupyter lab` to start either of the two apps.
Also see the documentation that is linked I the paragraph above.

---
## Resources
* [Earth and Environmental Data Science](https://earth-env-data-science.github.io/intro) full semester course by Ryan Abernathey at Columbia University from which much content is copied
* [IMAU's Python for Lunch workshop series](https://github.com/UU-IMAU/Python-for-lunch-Notebooks) a collection of workshop materials on topics of interest from IMAU students and researchers