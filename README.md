# Linear Regression Bike Sharing Assignment
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario.In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits. Our goal is to develop a model to find the variables which are significant the demand for shared bikes with the available independent variables. It will be used by the management to understand and manipulate the business strategy to meet the demand levels and meet the customer's expectations.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario.In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
- The company wants to know which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands
- Our goal is to develop a model to find the variables which are significant the demand for shared bikes with the available independent variables. It will be used by the management to understand and manipulate the business strategy to meet the demand levels and meet the customer's expectations.
- The dataset we are using here is 'day.csv'

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Demand of bikes depend on year, temp, weather(clear, light snow), season(spring and winter), month(Sept, Mar)

We can see that the equation of our best fitted line is:

cnt = 0.1141 + 0.2339 x yr + 0.0258 x workingday + 0.4291 x temp − 0.1175 x season_spring + 0.553 x season_winter + 0.0733 x mnth_sept + 0.0768 x weathersit_clear − 0.2235 x weathersit_lightsnow

Overall we have a decent model without overfitting issue, but I also acknowledge that there could be other factors which might influence the model which were removed during VIF analysis and also multicollinearity analysis like holiday, windspeed, humidity, etc.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Seaborn
- Matplotlib
- Numpy
- Pandas
- Sklearn
- statsmodel

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@supriyaKU23] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
