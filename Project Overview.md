This repository contains two main components of the Climate Analysis project:

Part 1: Complete Code for Data Analysis

The complete code for Part 1 can be found in the folder SurfsUp, with the filename Solution_Code_Part_1.ipynb.
This section focuses on data analysis using Python and Jupyter Notebook.
Part 2: Climate API

The code for the Flask API is located in the main folder sqlalchemy-challenge, with the filename app.py.
To test the API, run the code and navigate to the following URL in your browser:http://127.0.0.1:5001
Once there, you’ll see the following available routes:
/api/v1.0/precipitation: Returns JSON data for the last 12 months of precipitation.
/api/v1.0/stations: Returns JSON data for all stations in the dataset.
/api/v1.0/tobs: Returns JSON data for the most active station's temperature observations for the last 12 months.
/api/v1.0/<start>: Returns minimum, average, and maximum temperatures from the start date to the most recent data.
/api/v1.0/<start>/<end>: Returns minimum, average, and maximum temperatures for the date range specified.
To use the dynamic routes (/api/v1.0/<start> and /api/v1.0/<start>/<end>), append the desired date(s) in the YYYY-MM-DD format to the base URL. For example:
http://127.0.0.1:5001/api/v1.0/2017-01-01
http://127.0.0.1:5001/api/v1.0/2017-01-01/2017-01-15
