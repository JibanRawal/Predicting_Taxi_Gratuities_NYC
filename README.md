<h1 align="center">Predicting_Taxi_Gratuities_NYC</h1>

<section>
<h2>Overview</h2> <p>The goal of this project was to create a multiple linear regression and random forest model to predict high rider gratuity or not. This project utilized yellow taxi trips taken in New York City during 2017. The final random forest model performed with 86% accuracy and 72% precision determining what features were most important in separating low tippers from high tippers. Based on the model, the duration, distance, and cost of the trip were most influential in determining a generous tipper (>20%) vs a non-generous one (<20%). </p>
</section>

<section>
  <h2>Business Understanding</h2><p>According to salary.com the average salary for a New York Taxi Driver is around $45,000. This salary is significantly low compared to a median rent value of $6,500 per month. It is important to understand what factors encourage riders to leave tips in order to help drivers obtain a livable wage. </p>
</section>
<section>
  <h2>Data Understanding</h2><p>The NYC Taxi and Limousine Commission data came from 
<a href="https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page">NYC.gov</a>
    . The data consisted of approximately 408k unique trips and 18 features. The features included information on trip duration and destination, vendor used, toll information, and payment type. The bar chart below shows the breakdown of how many generous tippers (>20%) versus non-generous tippers that exist in the data set. </p>
</section>
