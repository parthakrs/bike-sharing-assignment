# Bike-Sharing system
> Built a linear regression model for the prediction of demand for shared bikes..


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The goal is to identify key factors shaping post-quarantine bike-sharing demand and formulate strategy to maximize profits.
- BoomBikes is aiming to develop a strategic business plan to revitalize its operations and boost revenues once the pandemic-induced lockdowns are lifted and the economy starts recovering.
- Business Problem: the focus is on understanding the post-quarantine demand for shared bikes in the American market. By identifying the factors that influence the demand for shared bikes.

- The data set is a csv file with the Bike sharing data


## Conclusions
- From R-Sqaured and adj R-Sqaured value of both train and test dataset we could conclude that the above variables can well explain more than 77% of bike demand.
- Coeffiencients of the variables explains the factors effecting the bike demand

- Based on final model top three features contributing significantly towards explaining the demand are:

 - Temperature (0.415443)
 - weathersit : Light Snow, Light Rain + Mist & Cloudy (-0.380896)
 - year (0.234455)

Hence, it can be clearly concluded that the variables `temperature` , `season`/ `weather situation` and `month`  are significant in predicting the demand for shared bikes .



## Technologies Used
- NumPy - version 1.20.3
- Seaborn - version 0.11.2
- MatplotLib - version 3.4.3
- Plotly - version 5.7.0
- statsmodels - version 0.12.2
- sklearn - version 0.24.2
- scipy - version 1.7.1
- pandas - version 1.3.4


## Acknowledgements

- This project was inspired by UpGrad tutorials on Bike-Sharing system Assignment(ML) on the learning platform


## Contact
Created by [@parthakrs] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
## License

This project is open source and available without restrictions."# Bike-Sharing system CaseStudy" 
