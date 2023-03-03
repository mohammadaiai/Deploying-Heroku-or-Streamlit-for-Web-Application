# Deploying Heroku or Streamlit for Creating Web Applications
This repository provides the instructions on how to deploy your Machine Learning (ML) or Deep Learning (DL) applications on the Heroku or Streamlit servers. 
## Heroku
To use Heroku for creating ML/DL web applications, you need these files:
1. **app.py** --> Your application file 
2. **Reqirements.txt** --> The libraries used in your application should all be included in this file
3. **Procfile**
4. **setup.sh**

Note that the files are case-sensitive and have to be as presented above. The example files are available in the **Heroku folder** in this repo.
After uploading the files in your repo, you have to create a Heroku account (if you do not have one) and connect it to your repo and deploy the app to generate a link for your ML/DL applicaion. 

## Streamlit
To use Streamlit for deploying your application, you need these files:
1. **app.py** --> Your application file 
2. **reqirements.txt** --> The libraries used in your application should all be included in this file
3. **packages.txt** --> Sometimes, you may need these packages (My personal experience).

Note that the files are case-sensitive and have to be as presented above (except the app.py file). The example files are available in the **Streamlit folder** in this repo. After uploading the files in your repo, you have to create a Streamlit account (if you do not have one) and connect it to your GitHub repo and select the app.py file for deployment. Note that the program has to be programmed in the Streamlit Python library, which is desinged for creating ML/DL applications.
