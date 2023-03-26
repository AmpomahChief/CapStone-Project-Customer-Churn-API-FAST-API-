# CUSTOMER CHURN API WITH FAST API

This projet is based on a Zindi challenge for an African telecommunications company(Expresso) that provides customers with airtime and mobile data bundles. The objective of this challenge is to develop a machine learning model to predict the likelihood of each customer “churning,” i.e. becoming inactive and not making any transactions for 90 days.

This repository contains an API built with FAST API  using the trained classified model. 

## Setup
For manual installation, you need to have Python3 on your system. Then you can clone this repo and being at the repo's root :: friendly_web_interface_for_ML_models> ... follow the steps below:

Windows:

        python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  

Linux & MacOs:

        python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  

NB: For MacOs users, please install Xcode if you have an issue.

## Execution
Run the demo apps (being at the repository root):

        python src/api.py


## Screenshots

These are screenshots of the interface

![](/screenshoots/API1.png)


![](/screenshoots/API2.png)

[Click this to open the docs in your browser](http://127.0.0.1:8000)

# Author
- [Bernard Ampomah]()


