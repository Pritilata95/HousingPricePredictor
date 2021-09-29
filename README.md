# HousingPricePredictor 
This is a housing price predictor based on ML techniques where users can search and see expected price range of properties based on various input parameters like BHK, furnishing status, desired floor area, etc. Data have been scraped from MagicBricks site and are of different parts of Kolkata like  Dhakuria, Gariahat, Jadavpur etc. Backend framework is built using Python and for frontend HTML, along with CSS, is used. 

The details and functions of individual scripts are as follow:
<br>hello.py: entry point of the python application
<br>Searcher.py: the main script that manages the program flow
<br>Scraper.py: script for getting data from MagicBricks server
<br>Predictor.py: script for property price prediction based on different input parameters
<br>Property.py: script defining various property parameters 

### Steps to run on local environment
- clone the repository
- $ pip install requirements.txt
- cd to repo
- $ python app.py
- the app is served on localhost:5000
