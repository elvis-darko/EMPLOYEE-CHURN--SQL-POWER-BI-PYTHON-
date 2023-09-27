# EMPLOYEE CHURN (SQL POWER BI PYTHON)

## PROJECT DESCRIPTION
This project is about employee churn at IBM. Data Analysisis done using SQL. Visualizations are made using Microsoft Power BI. Additionally, python is used to undertake further analysis and machine learning. A Streamlit App and Fast API will be built to deploy the best performing model on the web. These apps will help HR department determine employess who will be likely to churn in the near future.


Predict the Attrition of an employee based on the various factor given

Uncover the factors that lead to employee attrition and explore important questions such as ‘show me a breakdown of distance from home by job role and attrition’ or ‘compare average monthly income by education and attrition’.
[Alt text](https://github.com/elvis-darko/EMPLOYEE-CHURN--SQL-POWER-BI-PYTHON-/raw/main/Assets/images/ibm.jpeg)

## SUMMARY
| Code      | Name        |   Deployed App |
|-----------|-------------|:------|
|TZ 1       | IBM EMPLOYE CHURN  | STREAMLIT APP<br />FAST API APP|



# NOTES ON DATASETS
This the data about the employee on various factor influencing the attrition from the company.
<br />
 This is a fictional data set created by IBM data scientists

# SCREESHOTS OF DEPLOYED APP


# SETUP
It is recommended to have Virtual Studio Code or any other standard code editor on your local machine.<br />Install the required packages locally to your computer.

It is recommended that you run a python version 3.0 and above. 
You can download the required python version from [here](https://www.python.org/downloads/).

Use these recommended steps to set up your local machine for this project:

1. **Clone the repo :** To clone this repo, copy the url and paste it in your GitHub desktop or code editor on your local machine.
        
        https://github.com/elvis-darko/Team_Zurich_Capstone_Project.git

1. **Create the Python's virtual environment :** <br />This will isolate the required libraries of the project to avoid conflicts.<br />Choose any of the line of code that will work on your local machine.

            python3 -m venv venv
            python -m venv venv


2. **Activate the Python's virtual environment :**<br />This will ensure that the Python kernel & libraries will be those of the created isolated environment.

            - for windows : 
                         venv\Scripts\activate

            - for Linux & MacOS :
                         source venv/bin/activate


3. **Upgrade Pip :**<br />Pip is the installed libraries/packages manager. Upgrading Pip will give an to up-to-date version that will work correctly.

            python -m pip install --upgrade pip


4. **Install the required libraries/packages :**<br />There are libraries and packages that are required for this project. These libraries and packages are listed in the `requirements.txt` file.<br />The text file will allow you to import these libraries and packages into the python's scripts and notebooks without any issue.

            python -m pip install -r requirements.txt 

# MACHINE LEARNING MODEL DEPLOYMENT
## Run Streamlit App
A streamlit app was added for further exploration of the model. The streamlit app provides a simple Graphic User Interface where predicitons can be made from inputs.

- Run the demo app (being at the root of the repository):
        
        Streamlit run streamlit.app.py


# EVALUATION
The evaluation metric for this challenge is Area Under the Curve (AUC).

The values can be between 0 and 1, inclusive. Where 1 indicates the customer churned and 0 indicates the customer stayed with Expresso.

Our final work would look like this:

            user_id                                      CHURN
            00001dbe00e56fc4b1c1b65dda63de2a5ece55f9      0.98
            000055d41c8a62052dd426592e8a4a3342bf565d      0.12
            000081dd3245e6869a4a9c574c7050e7bb84c2c8      0.37


# RESOURCES
Here are some ressources you would read to have a good understanding of tools, packages and concepts used in the project:
- [How to improve machine learning models](https://neptune.ai/blog/improving-ml-model-performance)
- [Machine Learning tutorial - A step by step guide](https://github.com/eaedk/Machine-Learning-Tutorials/blob/main/ML_Step_By_Step_Guide.ipynb)
- [Create user interfaces for machine learning models](https://www.youtube.com/watch?v=RiCQzBluTxU)
- [Getting started with Streamlit](https://docs.streamlit.io/library/get-started)


## CONTRIBUTORS
| NAME  |   COUNTRY |   E-MAIL  |
|:------|:----------|:----------|
|ELVIS DARKO|GHANA|elvis_darko@outlook.com|
|FAITH BERIDA|NIGERIA| princesstoy07@yahoo.com |
|RICHMOND E.Y. ABAKE|GHANA| richie.abake@gmail.com |
|RICHMOND TETTEH| GHANA|  |
|JOSEPH GIKUBU| KENYA|gikubujoseph@outlook.com|
|MARIE GRACE KAGAJU |  RWANDA |  kagajugrace@gmail.com |
