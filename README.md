# IBM-DS-Capstone

## About:
In this capstone, I will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

## Methods:
### 1. Data Collection 
Included pulling records from the SpaceX REST API and web scraping public Wikipedia HTML data
### 2. Data Cleaning and Wrangling
Ensured data was prepped for exploratory analysis and machine learning model
### 3. EDA
Consisted of data visualization of key parameters, SQL filtering and representation of data, and mapping of launch records using Folium
### 4. Supervised Machine Learning - Classification
Performed predictive analysis using classification models: standardized data were split into train/test sets and fit using four types of
classification models, and best parameters were chosen with a grid search technique before assessing model accuracy for the best fit model from each
type.

## Results
All SpaceX launch sites are near the coast and not in high latitude areas.
The most successful launch site is KSC LC-39A.
We can predict landing success using a decision tree ML model with 88.9% accuracy.

## Report
The final report can be found
[here](report/ds-capstone-Yejun_Tu.pdf).

</div>





