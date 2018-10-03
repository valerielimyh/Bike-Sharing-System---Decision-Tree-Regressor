==========================================
Bike Demand Prediction
==========================================

=========================================
Background 
=========================================
Bike sharing system is a automatic rental service that allows users to rent a bike from Point A and return to Point B quickly and easily. This form of rental service has been gaining popularity in recent years in many developed countries, such as US, Canada, Europe and Singapore. Given the rising demand, predictive analytics is important to help businesses forecast future demand, which allows them to adjust their current systems and operations to meet the forecasted trends more readily. This fine-tuning enables the business to function more effectively which ultimately improves their bottom line. To do so, we will look at factors that predict the demand for bikes, based on historical data, and design models for prediction. 

=========================================
Associated tasks
=========================================

	- Regression: 
Predicting of bike rental demand for registered users vis a vis casual users based on the environmental factors 
In particular, decision tree regression is used because it captures the non linearity of the dataset and is more robust to outliers.
   

=========================================
Files
=========================================

	- Readme.txt
	- hour.csv : bike sharing counts aggregated on hourly basis. 17379 Records
    Dataset obtained from Kaggle https://www.kaggle.com/marklvl/bike-sharing-dataset

=========================================
Dataset characteristics
=========================================	

	- instant: record index
	- dteday : date
	- season : season (1:springer, 2:summer, 3:fall, 4:winter)
	- yr : year (0: 2011, 1:2012)
	- mnth : month ( 1 to 12)
	- hr : hour (0 to 23)
	- holiday : weather day is holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit : 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : Normalized temperature in Celsius. The values are divided to 41 (max)
	- atemp: Normalized feeling temperature in Celsius. The values are divided to 50 (max)
    - feeling_temp: Feeling temperature in Celsius (atemp*50)
	- hum: Normalized humidity. The values are divided to 100 (max)
	- windspeed: Normalized wind speed. The values are divided to 67 (max)
	- casual: count of casual users
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered
	
=========================================
License
=========================================
Use of this dataset in publications must be cited to the following publication:

[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

@article{
	year={2013},
	issn={2192-6352},
	journal={Progress in Artificial Intelligence},
	doi={10.1007/s13748-013-0040-3},
	title={Event labeling combining ensemble detectors and background knowledge},
	url={http://dx.doi.org/10.1007/s13748-013-0040-3},
	publisher={Springer Berlin Heidelberg},
	keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
	author={Fanaee-T, Hadi and Gama, Joao},
	pages={1-15}
}

=========================================
Contact
=========================================
	
For further information about this dataset please contact Hadi Fanaee-T (hadi.fanaee@fe.up.pt)
