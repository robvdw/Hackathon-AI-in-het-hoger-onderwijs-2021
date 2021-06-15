# Hackathon AI in het hoger onderwijs 2021
In teamverband bedenk je een AI-oplossing voor een casus in het hoger onderwijs. Stel een team samen van docenten, studenten en andere geïnteresseerden (6-8 personen) en meld je aan! De Hackathon wordt georganiseerd in samenwerking met de SURF SIG AI in Education en de Nederlandse AI Coalitie.
 
 https://versnellingsplan.nl/agenda/hackathon-ai/
 
Deze GitHub Repository is bedoeld voor de Hackathon Jedi Teachers. Bevat hulplijnen en tips om ML-coding te faciliteren via  SURF's JUPYTERHUB notebook webrowser interface.


# JupyterHub for education

What is JupyterHub?
JupyterHub provides a multiuser environment for Jupyter notebooks. The SURF JupyterHub service facilitates external courses, e.g. programming courses, and runs on our Lisa cluster.
Each course receives its own instance of JupyterHub. Users who log in will be provided with their own Jupyter Notebook Server, where they can create, download, upload and run notebooks. The service provides functionality for teachers to easily share notebooks, data and installations with their students.


https://servicedesk.surfsara.nl/wiki/display/WIKI/JupyterHub+for+education


# PIP: How to install AI platforms / software

====> terminal

## TENSORFLOW
https://www.tensorflow.org/install/pip?hl=sl
https://www.tensorflow.org/guide/data

pip install tensorflow  --ignore-installed --prefix=~/JHL_installations/Python

pip show tensorflow

## PYTORCH
https://pytorch.org/get-started/locally/

pip install torch torchvision --ignore-installed --prefix=~/JHL_installations/Python

## SciTech Learn
https://pypi.org/project/scikit-learn/

pip scikit-learn --ignore-installed --prefix=~/JHL_installations/Python

## KERAS
https://pypi.org/project/keras/

pip install keras torchvision --ignore-installed --prefix=~/JHL_installations/Python

## YELLOWBRICK
Yellowbrick is a suite of visual analysis and diagnostic tools designed to facilitate machine learning with scikit-learn. 
https://pypi.org/project/yellowbrick/

pip install yellowbrick --ignore-installed --prefix=~/JHL_installations/Python


# EXAMPLES: Python code to verify installed software

## TO DISPLAY DATA in NOTEBOOK using matplotlib

import matplotlib.pyplot as plt
import numpy as np
%matplotlib notebook
