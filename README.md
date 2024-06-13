
# Weather Ahead: Navigating the Future with Prediction

This project aims to develop a system that can reliably predict, at least 24 hours in advance, whether there will be a surplus of renewable energy (wind or solar) in a specific area. The goal is to enable the energy company to offer a new service where local clients near a source of renewable energy can receive free energy when there is a surplus in that area.

## Dataset
The dataset provided by the company spans from the year 2000 to the present day and contains historical records of energy data for the target area. This dataset serves as the foundation for training and validating our predictive models.

## Methods Used

* Machine Learning
* Data Visualization
* Predictive Modeling

## Needs of this project

* data exploration
* data processing
* cleaning
* modeling

## Approach
The approach for this project will involve the following steps:

1. **Data Preprocessing**: The initial step involves cleaning and preprocessing the dataset to ensure its quality and compatibility with machine learning algorithms. This includes handling missing values, removing outliers, and encoding categorical variables.
2. **Feature Engineering**: Feature engineering is crucial for enhancing the predictive power of our models. We'll derive new features from the existing dataset that capture important aspects related to energy production, consumption, weather patterns, and other relevant factors.
3. **Model Selection**: We'll explore and evaluate various machine learning models suitable for predicting energy surpluses. This involves comparing different algorithms, considering their performance metrics, and selecting the most appropriate ones for our task.
4. **Model Training and Evaluation**: Selected models will be trained on the preprocessed data and evaluated using appropriate evaluation metrics. Special attention will be given to minimizing false positives, as accurate predictions are essential for the success of our energy surplus forecasting system.
5. **Model Deployment**:The best-performing model will be integrated into a deployable system capable of making predictions and generating alerts for potential energy surpluses. This system will provide timely information to energy companies, enabling them to optimize resource allocation and offer value-added services to their clients.


## Code Organization
The code for this project is organized into the following Jupyter Notebooks:

- `preprocessing.ipynb`:This notebook focuses on data exploration, cleaning, and preprocessing steps. It ensures that the dataset is prepared for further analysis and model training.
- `prediction.ipynb`: Here, we deploy the best-performing model selected during training. This notebook is responsible for making predictions based on real-time or future data inputs.

## Usage
To utilize the project code, follow these steps:

1. Open Google Colab or any Python environment that supports Jupyter Notebooks.
2. Open and run the preprocessing.ipynb notebook to prepare the dataset.
3. Mention the correct drive path while loading the data set.
3. Proceed to run the prediction.ipynb notebook to deploy and use the predictive model.
Note: Avoid re-running the preprocessing code to prevent potential errors due to data transformations that cannot be repeated.

## Questions asked 
1. Confident about your model and if it fullfill the requirement of the company?
Answer: Yes. I had tried more than 4 machine learning models and two neural network models and used that for training and validation set to find the best hyper-parameter tuning.  Then I deployed the best predicted model for the prediction.

2. Is it ready to deploy in may month?
Answer: Yes.  It is ready to deploy in may month.  Just need the data till mey month.  If the data is there till may month then predictin accuracy will be much higher.

3. Limitations to be considered?
Answer: Some of the Assumptions like solar panel in colchester, wind turbine in colchester and energy consumed by colchester people per day these values are not that much accurate.  So just consider there assumptions while deploying in may month.

4. Any other insights from the data that can help company?
Answer:  Check the overall energy produced by the both solar and wind energy to identify the surplus energy.

## Assumptions
1. Electricity consumed per day in colchester.  This is Assumption.  Because I got the electricity consumed per year by the colchester people.  By this value I converted the value to one day by dividing it by 365.
Reference: https://www.colchester.gov.uk/sustainability/our-emissions/?id=&page=emissions--monitoring

2. Number of solar panels.  This is also a Assumption.  I have the total number of homes installed solar panel in house.  But not exactly how much solar panels are there in colchester.
Reference:  https://www.sunsave.energy/solar-panels-advice/uk-places/essex

3. Number of wind turbines.  This is also a Assumption.  I have the number of wind turbines in Over all Essex.  But I dont know the exact number for only in colchester.  
Reference: https://windsorstar.com/business/33698#:~:text=Combined%20with%20seven%20other%20wind,than%20350%20megawatts%20of%20electricity




