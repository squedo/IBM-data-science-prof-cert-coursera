Coursera_Capstone - IBM Data Science prof certification
INTRODUCTION:

Unfortunately, car accidents happen.

Would it be possible to understand/predict the severity of an eventual car driver accident if ever happening?

Such a predictive model could be interesting for instance for:

inssurance companies to set a final price for an inssurance.
for government authorities to forcast casualties that may occur during a year based on vehicles registered and drivers records an plan measures to reduce those casualties numbers.
for generate awareness in individuals so that they are aware of the need of replacing their car, be even more careful when it rains or when it's a foggy day, etc.
We will be exploring the feasibility of creating such a predictive model based on variables that could be stored into the following catergories:

Driver data (age, etc.)
Time, road and environmental conditions (visibility, weather conditions, moment of the year, etc.)
Car specifications (Engine capacity, driver side, etc)
Parameters of the accident (speed, point of impact, etc.)
Based on those variables the model would predict if a driver ever having an accident with an impact if it's going to be "fatal", "Serious" or "Slight" a certain probability (multiclass classification problem). We could also for simplicity, make the model to assist a binary classification model where based on the same variables we would be looking to predict between "fatal accidents" and "serious/slight" accidents.

To proceed we will be using the database published on Kaggle.com called "UK Accidents 10 years history with many variables" that collects accidents that took place from 2005-2014 in UK roads. Data are stored in 3 tables: accidents, vehicles and casualties and can be found in the following link: https://www.kaggle.com/benoit72/uk-accidents-10-years-history-with-many-variables

NOTE: this database is likely to give insights / prediction model to be used only for countries like UK, Japan, Australia, India (more that 50 countries) where traffic happens from left side.
