# food-vision-app-deployed-in-GCP

![food vision demo](https://github.com/jaimeggb/food-vision-app-deployed-in-GCP/blob/main/images/food-vision-demo-cropped.gif)

## Description: 
In this project I deployed a Streamlit-powered web application (Food Vision 🍔👁) for classifying images of food on Google Cloud.

The above GIF shows the web application running on Google Cloud making a live prediction on an image of ice cream using a machine learning model

Project Objectives:
- To deploy a Streamlit-powered web application using machine learing models hosted by Google Cloud servers.

What I learned from the projects:
- How to deploy a Streamlit-power web application
- How to use Google Cloud's App Engine
- How to use Google Cloud's AI Platform
- How to debug Streamlit deployments using the Git Bash terminal, App Engine logs, desk research and extensive trial and error

## How to use: 
1. Fork the repository by Daniel Bourke
2. Change the requirements.txt file to use streamlit==1.3.1 (this will save you hours of debugging)
3. Follow [this video](https://youtu.be/fw6NMQrYc6w) to its very end

## Technologies: 
- Google App Engine: to deploy the web application and host its required files
- Google AI Platform: to make the predictions with the stored machine learning models
- Google Storage: to store the machine learning models 
- Google Colab notebooks: to create the saved models
- Git Bash: to carry out deployment steps
- Git: for file version control
- Markdown: for this README.md file

## Collaborators: 
Done with the guidance of Daniel Bourke

## License: 
MIT License 
