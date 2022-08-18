<p align="right"><strong>English</strong> | <a href="https://github.com/joaocarnevalli/CP4_ML_1TDCF/blob/main/README.pt-br.md">Português</a></p>

# Machine Learning - Dr. Diabetes - Python #
Checkpoint #4 of FIAP Coding For Security
> - Objective: To develop a program based on the supervised machine learning technique.
> -  Challenge: How do I know if I have diabetes?

- - - - - - - - - - - - - - - - - - -
## Contents
* [Group](#group)
* [General Info](#general)
* [Fluxogram](#fluxogram)
* [Parameters](#parameters)
* [Technologies](#technologies)
* [Setup](#setup)

- - - - - - - - - - - - - - - - - - -
## Group
* **João Pedro Zobolli Carnevalli**
    - [GitHub](https://github.com/joaocarnevalli)
        - *@joaocarnevalli*
    - [Linkedin](https://www.linkedin.com/in/joaopedrozobollicarnevalli/)
    - [Twitch](https://www.twitch.tv/1joaolight)
    - **E-mail** 
        - **joaocarnevalli.sec@gmail.com**
* **Renato Kim**
    - [GitHub](https://github.com/renatokim18)
        - *@renatokim18*
    - [Linkedin](https://www.linkedin.com/in/renato-kim-722a69232/)
* **Gustavo Kondo**
    - [GitHub](https://github.com/GustavoKondo)
        - *@GustavoKondo*
    - [Linkedin](https://www.linkedin.com/in/gustavo-kondo-torres/)
* **Kaiky Amaral**
    - [GitHub](https://github.com/KekDisk)
        - *@KekDisk*

- - - - - - - - - - - - - - - - - - -
## General
This program aims to give a pre-diagnosis of diabetes based on the patient's glucose values ​​collected in three different states and situations. They are: Casual State, post overload and fasting. 
It can bring 3 different results.
* *Normal Glucose*
* *Decreased Glucose*
* *Diabetes Mellitus*

- - - - - - - - - - - - - - - - - - -
## Fluxogram
![Fluxogram](https://user-images.githubusercontent.com/109440123/185503733-e098478c-1e86-4ccc-871c-ce62dbce61b8.png)

- - - - - - - - - - - - - - - - - - -
## Parameters
* **Normal Glucose**
    - Fasting:
        - less than 100mg/dL
    - Post Overload: 
        - less than 140mg/dL
    - Casual blood glucose:
        - less than 200mg/dL
* **Decreased Glucose**
    - Fasting:
        - between 100 and 126 mg/dL
    - Post Overload: 
        - between 140 to 200mg/dL
    - Casual blood glucose:
        - less than 200mg/dL
* **Diabetes mellitus**
    - Fasting:
        - Greater than or equal to 126mg/dL
    - Post Overload:
        - Greater than or equal to 126mg/dL
    - Casual blood glucose:
        - greater than or equal to 200mg/dL
* **Criteria for evaluation**
    - Fasting: No food intake for at least 8 hours
    - Post Overload: 2h after 75g of glucose
    - Casual blood glucose: Performed at any time of day
###### Source: [GlicOnline](https://gliconline.net/tenho-diabetes/)

- - - - - - - - - - - - - - - - - - -
## Technologies
this project was made in [Python 3.10](https://www.python.org) using the [scikit-learn](https://scikit-learn.org/stable/) library

- - - - - - - - - - - - - - - - - - -
## Setup
* 1 - Install [Python](https://www.python.org/ftp/python/3.10.6/python-3.10.6-amd64.exe)
* 2 - Install [scikit-learn](https://scikit-learn.org/stable/install.html#) library
	- Open CMD
	- Type `pip install -U scikit-learn` and run it
* 3 - Download the `doctormachinelearning.py` and run it.


