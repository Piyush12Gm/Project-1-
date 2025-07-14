# Project-1
Mobile Phone Pricing
<img width="961" height="626" alt="image" src="https://github.com/user-attachments/assets/5ce9d006-a7ae-4120-9d52-e20a451b6e28" />


Introduction:
Mobile phones come in all sorts of prices, features, specifications and all. Price estimation and prediction is an important part of consumer strategy. Deciding on the correct price of a product is very important for the market success of a product. A new product that has to be launched, must have the correct price so that consumers find it appropriate to buy the product. We hope that with the help of a machine learning model, we can better estimate the pricing of our mobile phones and compete effectively with other players in the market.The data contains information regarding mobile phone features, specifications etc and their price range. The various features and information can be used to predict the price range of a mobile phone.

The data features are as follows:
id : ID
battery_power : Battery Power in mAh
blue : Has bluetooth or not
clock_speed : Microprocessor clock speed
dual_sim : The phone has dual sim support or not
fc : Front Camera Megapixels
four_g : Has 4G support or not
int_memory : Internal Memory in GigaBytes
m_dep : Mobile Depth in cm
mobile_wt : Weight of mobile phone
n_cores : Number of cores in the processor
pc : Primary Camera Megapixels
px_height : Pixel Resolution height
px_width : Pixel resolution width
ram : RAM in MB
sc_h : Mobile screen height in cm
sc_w : Mobile screen width in cm
talk_time : Longest time after a single charge
three_g : Has 3G or not
touch_screen : Has touch screen or not
wifi : Has wifi or not
price_range : This is the target variable with value of:

0 (low cost)
1 (medium cost)
2 (high cost)
3 (very high cost)
Methodology:
We will proceed with reading the data, and then perform data analysis. The practice of examining data using analytical or statistical methods in order to identify meaningful information is known as data analysis. After data analysis, we will find out the data distribution and data types. We will train 3 classification algorithms to predict the output. We will also compare the outputs. Let us get started with the project implementation. We finally predict the price range for 1000 usseen data.

Algorithms:
Support Vector Machine (SVM)
Decision Tree (DT)
Random Forest (RF)
