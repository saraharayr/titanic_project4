# Birmingham Housing Price Predictor
Machine Learning Project 4

## Background 

Based on data gathered from the UK's Government Website, the Department for Levelling Up, Housing & Communities API, The Transport for West Midlands API, and The Police API. We wanted to create a Machine Learning Model that is able to predict House Prices in the city of Birmingham, UK; based on certain features, such as crime rate, housing features, schools around the area, and easy access to transportation.

![image](https://user-images.githubusercontent.com/93007493/166536604-b6de04b9-60db-44d5-8045-fcaaa0e56e33.jpeg)

## About the Data

!<img width="224" alt="image" src="https://user-images.githubusercontent.com/93007493/166538791-fcf4e7b7-bf21-44bd-b773-c1b8edbe9ef2.png">
!<img width="225" alt="image" src="https://user-images.githubusercontent.com/93007493/166538953-b6e985ff-5b89-4a25-a8d5-925cb163d5dc.png">
!<img width="224" alt="image" src="https://user-images.githubusercontent.com/93007493/166539072-84264dbe-cc2c-400d-85bc-25a01fcaecf3.png">
!<img width="224" alt="image" src="https://user-images.githubusercontent.com/93007493/166539199-03107a9f-03bf-4581-b9a1-2e1186f052fb.png">

### Data Collection 
- We used Jupyter Notebook and Pandas to call different APIs, and create a data set that was suitable for the model. Taking into consideration the feautures we found the most relevant:
-   Crime Rates
-   Transportation
-   Schools in the area
-   Property type

[Visualisation of the Data using Tableau](https://public.tableau.com/shared/85JZW3QTT?:display_count=n&:origin=viz_share_link)

## Softwares and libraries used 
This project uses the following software and Python libraries:
- [Python] (https://www.python.org/download/releases/3.0/)
- [NumPy] (https://numpy.org/)
- [pandas] (https://pandas.pydata.org/)
- [scikit-learn] (https://scikit-learn.org/stable/) 


## Machine Learning Models

- Random Forest Classifier
- Linear Regression/Logistic Regression


## Hypothesis and Predictions
- Random forest tends to be the ideal candidate for estimating datasets that are more longitudinal in nature with more complexity and randomness, and usually scaling and preprocessing the data does not affect its results, so our guess is it will perform better in this case.

## Final Score
- Unscaled:

Logistic Regression Training Data Score: 0.46834462729912874

Logistic Regression Testing Data Score: 0.4465737514518002

![2022-10-11](https://user-images.githubusercontent.com/92040392/195129830-f25a1687-d813-4835-a201-9565e150c735.png)

RFC Training Score: 0.543272023233301

RFC Testing Score: 0.3826945412311266

![2022-10-11 (1)](https://user-images.githubusercontent.com/92040392/195130775-09c4a1a0-0518-4de1-8213-9a7558ea6e20.png)

- Scaled:

Logistic Regession Training Data Score: 0.47221684414327203

Logistic Regression Testing Data Score: 0.4465737514518002

![2022-10-11 (2)](https://user-images.githubusercontent.com/92040392/195131344-55745a19-8b97-4619-bbac-be90571d6ed7.png)

RFC Training Data Score: 0.543272023233301

RFC Testing Score: 0.3826945412311266

![2022-10-11 (3)](https://user-images.githubusercontent.com/92040392/195131791-7d422a1f-4dfb-4bb0-9b52-61cc7a2ec630.png)

## Conclusion
- Unlike our hypothesis suggested, Logistic Regression perfomed better than RFC.
- The scores were unaffected by scaling. 
- We did not produce feature optimisation, so further features could be added.
- The model runs well, but accuracy levels could be improved.


## Further Considerations

1. Do you think your model is sufficiently able to capture all the advanced factors that can affect house prices in any area?
2. What is the most critical parameter you think to decide the price of any house?
3. Why do we need Machine Learning models to solve the problem of house price prediction?
4. What are the factors that affect house prices?
5. Which machine learning models can be used to predict house prices?


