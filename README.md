# RealEstate-Price-Prediction
The real estate price prediction can be used in the informative and
search for property prices in a particularly chosen city (Banglore in
this case). It can predict the price of property based on various
features like area, number of bedrooms, and number of bathrooms
and the locality on which its price depends.
The goal of this project is to take data from a dataset and predict the
price based on various features. The project used various Data
Science and Machine Learning concepts, it also used python flask
framework for server building. For building the web UI technologies
like HTML, CSS and JavaScript has been used.

<h2>Project Architecure</h2>
<ul><li>We took a home price dataset from kaggle.com .The dataset
used in this project is for Banglore city, India.
</li>
<li>Using this dataset we built a machine learning model. Building
this model we covered some of major data science concepts
like data cleaning, feature engineering, outlier removal
,dimensionality reduction etc.
</li>
<li>After we built the model, we exported it to a pickle file, then
we made a python flask server which can consume this pickle
file and do price prediction.
</li>
<li>This python flask server exposed HTTP endpoints for various
requests and UI is written in HTML CSS and Javascript and
makes HTTP Get and Post calls.
</li>




