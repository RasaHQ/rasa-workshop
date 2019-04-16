# Building AI assistants that scale using machine learning and open source tools

This is a repository for a 3-hour workshop at O'Reilly AI Conference 2019 run by Justina Petraityte, Developer Advocate at Rasa. The actual exercise will be uploaded here before the workshop, but you can already use this repository to set up your environment.


## Software used in this workshop
During this workshop, we will program everything in Python. To successfully follow the workshop your environment should contain:  
- Python <= 3.6.8 (python 3.6.8 is recommended and having anaconda installed will make things easier)
- Jupyter notebook 


During this workshop we will use only open source tools and software:  
- rasa NLU  
- rasa Core  
- sqlite3  
- pandas  
- mongodb  

Additional tools you will need to successfully follow this workshop:  
- Text editor  
- Web browser  
- Terminal  


## Installation

To install the required python modules you can create a virtual environment and install all the required dependecies there using a requirements.txt file provided in this repo:

1. Create a conda environment:
`conda create -n rasa-workshop python=3.6.8`

2. Activate the environment:
`conda activate rasa-workshop`

3. Install the requirements:
`pip install -r requirements.txt`


If you don't want to use virtual environments, you can install the dependecies directly on your system using a requirements.txt file provided in this repo:

`pip install -r requirements.txt`


One of the steps in this workshop will also include using a Mongo DB. It's an optional step, but if you want to follow along, make sure to install Mongo DB on your machine as well. You can find the installation intructions for all operating systems [here](https://docs.mongodb.com/manual/installation/).


## What's in this repository

This repository consists of a few jupyter notebooks and some additional files:

- **rasa_workshop_exercise.ipynb** - is a completed exercise which has all the code implemented. 
- **rasa_workshop_starter.ipynb** - is a notebook which we will complete liive during the workshop.
- **help files** - a direcotry which contans some help files in case things go wrong during the workshop :)  
- **bot_ui** - a directory which contains a code for chat UI and a simple html webpage which we will use to connect our assistant to  
- **Makfile** - a file with some bash commands which you can use to train and run the assistant without jupyter notebook 
- **ConfDB.db** - a little sqlite3 database which we will use during the workshop   


## Get in touch

If you encounter any problems while installing the dependencies or have any questions, shoot me a message at juste@rasa.com
