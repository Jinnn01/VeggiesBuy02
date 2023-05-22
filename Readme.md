# VeggiesBuy

Welcome to VeggiesBuy, the ultimate platform for comparing vegetable prices and making informed purchasing decisions. This README file will guide you through the application's features, installation process, and usage instructions.

## Features

VeggiesBuy offers the following key features to enhance your shopping experience:

1. Home View: The central interface of the app, providing easy navigation and access to various features.
2. Map View: Displays supermarket locations and product information, making it convenient to compare prices across different stores.
3. Upload Function: Allows users to add vegetable prices to the app using manual entry or OCR (Optical Character Recognition) for quick scanning of barcodes.

## Installation
To get started with VeggiesBuy, follow these steps:

### Front-end (SwiftUI)
Clone the repository: `git clone https://github.com/Jinnn01/VeggiesBuy.git`
Open Xcode and navigate to the project folder.
Build and run the project in Xcode.
The VeggiesBuy app will launch in the simulator or on your connected iOS device.

### Back-end (Python Flask)
Ensure you have Python installed on your system. You can download it from the official Python website.
Clone the repository: `git clone https://github.com/Jinnn01/VeggiesBuy.git`
Create a virtual environment (optional but recommended): `python -m venv env`
Activate the virtual environment:
On macOS/Linux: `source env/bin/activate`
On Windows:` .\env\Scripts\activate`
Install the required Python packages: `pip install -r requirements.txt`
Start the Flask development server:` python app.py`

## Files
1.	VeggiesBuy: This directory contains the main source code and files for the VeggiesBuy application, including HomeView, MapView, UploadView etc.
2.	VeggiesBuyTests and VeggiesBuyUITests: These directories contain test files. 
3.	models: This directory includes files related to data models or database schemas used in VeggiesBuy, including ocr and manually upload functions.
4.	node_modules: It contains the dependencies and packages required for the frontend development of VeggiesBuy.
5.	resources: This directory contains main source code related to API setting of VeggiesBuy application.
6.	Authentication: This directory contains all files related to signIn and signUp pages.
7.	.flaskenv: This file contains environment variables specific to the Flask backend. 
8.	Dockerfile: This file is used in Docker containerization, specifying the instructions to build a Docker image for deploying the VeggiesBuy application.
9.	app.py: This file is the main entry point for the Flask backend of VeggiesBuy. It contains the application's routing, API endpoints, and business logic.
10.	data.db: Database file which contain tables, records, and other relevant data structures including 66 records of vegetables.
11.	db.py: This file set connection to database.
12.	requirements.txt: This file lists the Python dependencies and libraries required for running the VeggiesBuy application. 
13.	schemas.py: This file defines the data schemas or data validation rules used in VeggiesBuy. 


## Feedback
We value your feedback and contributions to make VeggiesBuy even better. If you encounter any issues or have suggestions for improvement, please submit them through the issue tracker on our GitHub repository.





