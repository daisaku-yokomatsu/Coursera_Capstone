## About the Data to be Analyzed

In this section, we will use the following data for our analysis.

### Subway Stations
To use New York City subway stations as a base, we will obtain data on station locations (latitude and longitude) from the NYC OpenData website:

https://nycopendata.socrata.com/Transportation/Subway-Stations/arq3-7z49

### Apartment Data
For the apartment data, we will use the data of airbnb properties in New York. However, the data is not officially provided by airbnb, but is collected by volunteers and made available to the public. The data can be obtained from the following website:

http://insideairbnb.com/get-the-data.html

The data includes property types, locations (latitude, longitude), user score ratings,etc. Since the airbnb data includes a wide variety of properties, the following conditions should be applied:

	-Properties should be limited to whole apartments and serviced apartments.
	-The maximum length of stay of the property must be at least 90 days. 
	-The property must have a user rating score of 95 or higher on a 100-point scale.
	-Properties must be within a 300 meter radius of a subway station.

### The Supermarket Data
The supermarket data will be obtained using Foursquare's API.
	-Focus on stores within a radius of 500 meters from the subway station.
The API allows us to filter the 'venues' by the type of store. We can get the data by calling the API with the code that represents the supermarket.

