### Movie Recommendation System Web App

## Overview
This web application is a Movie Recommendation System built using Flask, a lightweight Python web framework. The system recommends movies to users based on their preferences and viewing history. The app is designed to be deployed on the Azure cloud platform.

## Features
User Authentication: Users can create accounts, log in, and track their movie preferences.
Personalized Recommendations: The system provides movie recommendations based on user preferences and viewing history.
Search Functionality: Users can search for movies and get detailed information about each movie.
User Ratings: Users can rate movies, and the system uses this information to improve recommendations.

## Prerequisites

Make sure you have the following installed:

Python 3.x
Flask
Azure account

## Setup
Clone the repository:
https://github.com/sanjeeviss/Content-Based-Movie-Recommendation-System

## Set up Azure:
Create an Azure account if you don't have one.
Create a new web app in Azure and note down the app URL.
Configure your Flask app with Azure credentials (client ID, client secret, etc.).

## Configure the app:
Update the config.py file with your Azure configuration and database details.

## Run the app:
python app.py

## Deployment to Azure
Deploy the app to Azure:

## Step 1: Set Up Azure Resources
Create a Resource Group:

Log in to the Azure Portal.
Navigate to "Resource groups" and create a new resource group to organize your resources.
Create an Azure Web App:

In the Azure Portal, go to the resource group you just created.
Click on the "+ Add" button to add a new resource.
Search for "Web App" and select "Web App" from the list.
Fill in the required information, such as the name, subscription, resource group, and other settings.
Choose the runtime stack (Python) and the operating system.
Review and create the web app.

## Step 2: Configure Deployment Settings
Configure Deployment Source:

In the Azure Portal, go to your Web App.
Navigate to "Deployment Center" under the "Deployment" section.
Choose the source code repository where your Flask app is hosted (e.g., GitHub, Azure Repos, Bitbucket).
Set Up Deployment Options:

Configure the deployment options based on your source code repository. For example, if using GitHub, authenticate and select the repository and branch.

## Step 3: Configure Virtual Network (VNet)
Create a Virtual Network:

In the Azure Portal, navigate to "Virtual networks."
Create a new virtual network to host your web app.
Integrate Web App with VNet:

In the Web App settings, go to the "Networking" section.
Enable the "VNet Integration" option and select the virtual network you created.

## Step 4: Integrate with Azure Cognitive Services (Optional)
Create Azure Cognitive Services Resource:

Create a new resource of the type you need, such as "Language Understanding" or "Text Analytics."
Note the endpoint and access keys provided by the service.
Configure Flask App to Use Cognitive Services:

Update your Flask app code to make API calls to the Azure Cognitive Services.
Use the obtained endpoint and access keys in your app's configuration.

## Step 5: Deploy Flask App
Push Changes to Repository:

Ensure that your Flask app code contains the necessary changes to work with Azure and any integrated services.
Trigger Deployment:

Push the changes to your source code repository.
Azure should automatically detect the changes and trigger the deployment.
Monitor Deployment:

Monitor the deployment process in the Azure Portal. Check for any errors or issues in the deployment logs.
Access the Deployed Web App:

Once deployed, access your Flask web app using the URL provided by Azure.

## Open the deployed app in your browser:
az webapp browse --name your-movie-recommendation-app
This command will open the web app in your default browser.

## Usage
Create an account or log in.
Explore movies, search for your favorites, and rate them.
Receive personalized recommendations based on your preferences.

## Contributing
Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.







## SCREENSHOTS:

[](![Screenshot 2023-11-09 115950](https://github.com/sanjeeviss/Content-Based-Movie-Recommendation-System/assets/113248194/066104f7-2b39-46fd-8a28-f4850f2b4b40)
![Screenshot 2023-11-09 120023](https://github.com/sanjeeviss/Content-Based-Movie-Recommendation-System/assets/113248194/117e0e7a-b589-4ea3-a7c6-17d1bc170930)
![Screenshot 2023-11-09 120144](https://github.com/sanjeeviss/Content-Based-Movie-Recommendation-System/assets/113248194/26d8d401-6eb6-42e3-a28b-e15538942952))


