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

bash
Copy code
git clone https://github.com/yourusername/movie-recommendation-app.git
cd movie-recommendation-app
Install dependencies:



Create an Azure account if you don't have one.
Create a new web app in Azure and note down the app URL.
Configure your Flask app with Azure credentials (client ID, client secret, etc.).
Configure the app:

Update the config.py file with your Azure configuration and database details.
Run the app:

bash
Copy code
python app.py
Access the app at http://localhost:5000 and make sure everything is working locally.

Deployment to Azure
Deploy the app to Azure:

bash
Copy code
az webapp up --sku F1 --name your-movie-recommendation-app --location your-region
Replace your-movie-recommendation-app with your desired app name and your-region with the Azure region you prefer.

Open the deployed app in your browser:

bash
Copy code
az webapp browse --name your-movie-recommendation-app
This command will open the web app in your default browser.

Usage
Create an account or log in.
Explore movies, search for your favorites, and rate them.
Receive personalized recommendations based on your preferences.
Contributing
Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.









## SCREENSHOTS:

[](![Screenshot 2023-11-09 115950](https://github.com/sanjeeviss/Content-Based-Movie-Recommendation-System/assets/113248194/066104f7-2b39-46fd-8a28-f4850f2b4b40)
![Screenshot 2023-11-09 120023](https://github.com/sanjeeviss/Content-Based-Movie-Recommendation-System/assets/113248194/117e0e7a-b589-4ea3-a7c6-17d1bc170930)
![Screenshot 2023-11-09 120144](https://github.com/sanjeeviss/Content-Based-Movie-Recommendation-System/assets/113248194/26d8d401-6eb6-42e3-a28b-e15538942952))


