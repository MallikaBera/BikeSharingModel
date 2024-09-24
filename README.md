# Machine Learning Model for Rental Bike Sharing 
BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

![bike_sharing_image](https://github.com/user-attachments/assets/90a29b7f-77b0-4078-95cc-8e93ec5e6fd6)

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
<!-- You can include any other section that is pertinent to your problem -->

## General Information
In the dataset provided, there are three columns named 'casual', 'registered', and 'cnt'. The variable 'casual' indicates the number casual users who have made a rental. The variable 'registered' on the other hand shows the total number of registered users who have made a booking on a given day. Finally, the 'cnt' variable indicates the total number of bike rentals, including both casual and registered. The model is built taking this 'cnt' as the target variable.

The model is trained on pre-defined dataset, i.e, it has have a supervised learning.
The target variable 'cnt' (count of total rental bikes including both casual and registered) is a continuous variable. 

Hence, it a Linear Regression Model for the analysis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
**Features**:     
The variables which are significant in predicting the demand for shared bikes - 
- year 
- temperature
- humidity
- windspeed
- Season (summer,winter)
- Weather Situation (Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist , Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds)
- Month (December, January , July, November, September)
- Weekday (Monday, Sunday)      

**Model Assumptions**:    
The residuals from the model confirms our assumptions for Model Error Analysis : 
- Linearity : The predictor variables and target variable have linear relationship
- Error terms are normally distributed with their mean residing at 0
- Error terms are independent of each other
- Error terms have constant variance

**Model Evaluation**:            
Mean Absolute Error : 0.071       
Mean SQ Error: 0.009        
Root Mean SQ Error: 0.095      
R-SQ : 0.811

The Actual data and the predicted data show enough closeness to conclude that the model can predict bike demands fairly well.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@MallikaBera] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project --># BikeSharingModel
