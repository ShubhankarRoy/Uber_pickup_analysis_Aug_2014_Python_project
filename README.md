# Uber_pickup_analysis_Aug_2014_Python_project

UBER PICKUPS IN NYC
In this project, we are going to analyse the Uber Pickups in New York City.
ABOUT THE DATASET
The dataset provided contains data on over 4.5 million Uber pickups in New York Cityfrom April to September 2014, and 14.3 million more Uber pickups from January toJune 2015.
Uber trip data from 2014
There are six files of raw data on Uber pickups in New York City from April toSeptember 2014. The files are separated by month and each has the followingcolumns:
Date/Time
: The date and time of the Uber pickup
Lat
: The latitude of the Uber pickup
Lon
: The longitude of the Uber pickup
Base
: The TLC (Taxi & Limousine Commission) base company code affiliatedwith the Uber pickup
These files are named:
uber-raw-data-apr14.csv
uber-raw-data-aug14.csv
uber-raw-data-jul14.csv
uber-raw-data-jun14.csv
uber-raw-data-may14.csv
uber-raw-data-sep14.csv
Uber trip data from 2015
Also included is the
file uber-raw-data-janjune-15.csv
. This file has thefollowing columns:
Dispatching_base_num
: The TLC base company code of the base thatdispatched the Uber
Pickup_date
: The date and time of the Uber pickup
Affiliated_base_num
: The TLC base company code affiliated with the Uberpickup
locationID
: The pickup location ID affiliated with the Uber pickup
The
base
codes are for the following Uber bases (In the parentheses, we have codenames in German which are used internally by Uber to categorize and manage theirvarious service offerings.) :
B02512 (Unter): This corresponds to the Uber service category "UberX", which
is the basic and most common service offering.
B02598 (Hinter): This corresponds to the Uber service category "UberPOOL",
which allows riders heading in the same direction to share a ride and split the
cost.
B02617 (Weiter): This corresponds to the Uber service category "UberXL",
which offers larger vehicles such as SUVs and minivans for accommodating
more passengers.
B02682 (Schmecken): This corresponds to the Uber service category
"UberSELECT", which provides premium rides with high-end vehicles.
B02764 (Danach-NY): This corresponds to the Uber service category
"UberWAV", which offers wheelchair-accessible vehicles for riders with
accessibility needs.
B02765 (Grun): This corresponds to the Uber service category "UberBLACK",
which provides luxury black car services with professional drivers.
B02835 (Dreist): This corresponds to the Uber service category "UberSUV",
which offers larger luxury vehicles for accommodating more passengers.
B02836 (Drinnen): This corresponds to the Uber service category "UberLUX",
which provides high-end luxury vehicles for a premium ride experience.
