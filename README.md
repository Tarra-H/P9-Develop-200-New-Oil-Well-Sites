# Develop 200 New Oil Well Sites

Project Description:

You work at the OilyGiant mining company. Our task is to find the best locations to develop 200 new oil well sites.

To accomplish this task, you must follow these steps:

Read files with parameters collected from oil wells in selected regions: oil quality and reserve volume;
Create a model to predict the reserve volume in new wells;
Select oil wells with the highest estimated value;
Choose the region with the highest total profit from the selected oil wells.
We have oil sample data from three regions. The parameters of each oil well in these regions are already known. Create a model that will help us choose the region with the highest profit margin. Don't forget to use bootstrapping techniques to analyze potential profits and risks.


Objective:
To find the best locations to develop 200 new oil well sites.


Project Instructions:

Download and prepare the data. Explain the procedures you perform.
Train and test the model for each region in 'geo_data_0.csv':

2.1. Split the data into a training set and a validation set with a ratio of 75:25.

2.2. Train the model and make predictions for the validation set.

2.3. Save the predictions and the correct answers for the validation set.

2.4. Display the predictions of the average volume of bookings and the RMSE of the model.

2.5. Analyze the results.

2.6. Perform and run steps 2.1-2.5 for the files 'geo_data_1.csv' and 'geo_data_2.csv'.

Prepare for profit calculation:

3.1. Save all the values needed for profit calculation in separate variables.

3.2. With an investment of 100 million for 200 oil wells, an average oil well must generate at least 500 thousand USD to avoid losses (this is equivalent to 111.1 units). Compare this amount with the average bookings in each region.

3.3. Provide a conclusion regarding the preparation you did in the profit calculation step.

Create a function to calculate profit from a selected set of oil wells and model predictions:

4.1. Write a function to calculate the profit from a selected set of oil wells and its model predictions: Select 200 wells with the highest predicted values from each of the 3 regions (csv files).

4.2. Summarize the target booking volume based on these predictions. Save the predictions for 200 wells in each of the 3 regions.

4.3. Deliver your conclusion: suggest a region suitable for oil well development and provide reasons for your choice. Calculate the profit for the received booking volume.

Calculate the risk and profit for each region:

5.1. Using the predictions saved in step 4.2, use bootstrapping technique with 1,000 samples to find the profit distribution.

5.2. Find the average profit, 95% confidence interval, and risk of loss. Loss is negative profit, calculated as a probability, and then expressed as a percentage.

5.3. Deliver your conclusion: suggest a region suitable for oil well development and provide reasons for your choice. Does this choice align with your previous choice in step 4.3?
