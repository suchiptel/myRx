# myRx
Congressional App Challenge Submission 2022 - An AI &amp; ML technology driven mobile application that analyzes food and drug interactions ease to address concerns about multi-drug use. 

## Microsoft Azure AI Backend
The backend service I relied on to support my myRx application.

## Tech/framework used
<b>Built with</b>
- [PyFlask](https://flask.palletsprojects.com/en/2.1.x/)
- [Azure ML] (https://azure.microsoft.com/en-us/services/machine-learning/)
- [Azure Virtual Machine] (https://azure.microsoft.com/en-us/services/virtual-machines/)
- [Azure SQL Database] (https://azure.microsoft.com/en-us/products/azure-sql/database/)

## Features
- **Azure SQL database** will securely store all the data collected from the users.
- I've utilized the **Azure Machine Learning** in order to optimize and test the machine learning models.
- The backend service for this app is deployed on **Azure Virtual Machine** as well as our trained ML model.
- I referenced the ML model from a PNAS paper about drug-drug and drug-food interaction (https://www.pnas.org/doi/10.1073/pnas.1803294115)
- Many of the medical termsm side-effects, and drug-drug interactions are difficult and complex to understand for the primary users. So, I've decided to utilize the **Webster's Medical Dictionary API** so a better experience can be provided for the user to understand hard verbiage in lay man's terms. 

## How to start the backend server?
1. ssh in Microsoft Azure VM.
2. `$ cd ~/microsoft_ai_hack_backend`
3. `$ export FLASK_APP=application`
4. `$ python3 application.py` Note: The server will only run on 10000 port
5. Ip address is 20.231.217.74.

## Credits/Contributors
<b>DDI/DFI Machine Learning Service</b>
Google API and Microsoft Azure AI
<b>Backend Service</b>
- Paper reference: https://www.pnas.org/doi/10.1073/pnas.1803294115

## License
MIT © [Suchi Patel] (https://github.com/suchiptel/myRx)
