<h1>Car Dekho Price Prediction</h1>

<hr>

<h3>Objective</h3><a id="1"></a>
<p>In this project, the objective is to predict Car Selling Price on various features like Car's Present_Price, Kms_Driven, Owner, Fuel_Type, Seller_Type, Transmission. We will use the CAR DEKHO dataset from Kaggle. This dataset contains information about used cars listed on <a href='www.cardekho.com'><u>website</u></a></p>


<br><p>We can predict Car Selling Price by filling the data over UI and after that prediction will be displayed over UI.</p>

<h3>Dataset Prview</h3><a id="3"></a>
A preview of top five rows of the Car Dekho dataset.

| | Car_Name | Year | Selling_Price | Present_Price | Kms_Driven | Fuel_Type | Seller_Type | Transmission | Owner |
|-| -------- | ---- | ------------- | ------------- | ---------- | --------- | ----------- | ------------ | ----- |
|0|     ritz | 2014 |	       3.35 |          5.59 |	   27000 |	  Petrol |	    Dealer |       Manual |     0 |
|1|      sx4 | 2013 |          4.75 |	       9.54 |	   43000 |    Diesel |	    Dealer |	   Manual |	    0 |
|2| 	ciaz | 2017	|          7.25 |          9.85	|       6900 |	  Petrol |  	Dealer |	   Manual |	    0 |
|3|  wagon r | 2011 |	       2.85 |	       4.15	|       5200 |	  Petrol |	    Dealer |	   Manual |	    0 |
|4|    swift | 2014 |          4.60	|          6.87	|      42450 |    Diesel |   	Dealer |       Manual |	    0 |

<h3>Description of variables in the dataset</h3><a id="4"></a>
Above dataset contains information about used cars listed on <a href='www.cardekho.com'><u>website</u></a>. This data can be used for a lot of purposes such as car price prediction using Machine Learning algorithms.
The columns in the given dataset are as follows:

```Car_Name:``` Name of Car sold

```Year:``` Year in which car was bought

```Selling_Price:``` Price at which car sold

```Present_Price:``` Price of same car model in current year 

```Kms_Driven:``` Number of Kilometers Car driven before it is sold

```Fuel_Type:``` Type of fuel Car uses

```Seller_Type:``` Type of seller 

```Transmission:``` Gear transmission of the car (Automatic / Manual)

```Owner:``` Number of previous owners 
 
<h3>Car Price Prediction directory tree</h3><a id="5"></a>

```
├─ Templates
│  └─ index.html
│
├─ app.py
│
├─ demo.gif
│
├─ rf_regression_model.pkl
│  
├─ Car Dekho Price Prediction.ipynb
│
├─ LICENSE
│  
├─ car data.csv
│
├─ Procfile
│
├─ README.md 
│
└─ requirements.txt
    
```
    
```Templates``` : contains templates for UI

```app.py``` : Front and back end portion of the web application

```Car Dekho Price Prediction.ipynb``` : conatains ipynb file (Jypiter Notebook file)

```rf_regression_model.pkl```  : contains model for prediction

```requirements.txt``` : required libraries 

```car data.csv```  : conatins raw data as csv file

<h3>Installation</h3><a id=""></a>

* Clone this repository and unzip it.

* create new env with python 3 and activate it .

* Install the required packages using pip install -r requirements.txt

* Execute the command: python app.py

* Open ```http://127.0.0.1:5000/``` in your browser.


## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
