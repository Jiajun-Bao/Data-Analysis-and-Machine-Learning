Name: Jiajun Bao

This program analyzes the relationship between features of light-duty vehicles
such as engine size, vehicle classification, number of cylinders, etc., and
their carbon dioxide emissions using Pandas and Altair. Then the program
utilizes machine learning Sklearn library to predict carbon dioxide emissions
for new light-duty vehicles and analyze and interpret which features are the
most informative for how a decision is made in the machine learning model.

Steps to run the code:
(1) install any of the following libraries if haven't so by typing the
    following command: pip install (library name). There should be no error
    messages if all the required libraries have been installed.
(2) The data set 2021_Fuel_Consumption.csv should have been downloaded and
    avalibale under the same folder of this notebook.If not, the dataset can
    be accessed at: https://www.nrcan.gc.ca/sites/nrcan/files/oee/files/csv/     
    MY2021%20Fuel%20Consumption%20Ratings.csv and the data file needs to be 
    saved in the same fodler as the Jupyter Notebook.
(3) Then run the Python code to in the order of the current Jupyter Notebook.
    Wrong order may lead to unexpected errors. Please contact me at 
    Jiajunb@uw.edu if you have any further questions.

Understanding the date table					
Model	
    4WD/4X4 = Four-wheel drive				
	AWD = All-wheel drive				
	FFV = Flexible-fuel vehicle				
	SWB = Short wheelbase				
	LWB = Long wheelbase				
	EWB = Extended wheelbase	

Transmission	
    A = automatic				
	AM = automated manual				
	AS = automatic with select shift				
	AV = continuously variable				
	M = manual				
	3 – 10 = Number of gears
				
Fuel type	
    X = regular gasoline				
	Z = premium gasoline				
	D = diesel				
	E = ethanol (E85)				
	N = natural gas		

Fuel consumption	
City and highway fuel consumption ratings are shown in litres per 100
kilometres (L/100 km) - the combined rating (55% city, 45% hwy) is shown
in L/100 km 

Tthe tailpipe emissions of carbon dioxide (in grams per kilometre) for
combined city and highway driving	

CO2 rating	the tailpipe emissions of carbon dioxide rated on a scale from
1 (worst) to 10 (best)				

Smog rating	the tailpipe emissions of smog-forming pollutants rated on a scale
from 1 (worst) to 10 (best)