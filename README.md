# Neural_Network_Charity_Analysis
Neural Networks and Machine Learning
## Overview
The main purpose of this challenge was to determine features from the given dataset and create binary classifiers that would help predict if applicants would be successful if funded by Alphabet Soup. The dataset contained over 34,000 applicants and our job was to organize and process the data to determine the success percentage. 
## Results
- The target variable in my model is the "Is Successful" column.
- The features in the model are every column except for the target variable of "Is Successful".
- Columns that were unncessesary and therefore dropped at the beginning were the "EIN" and "Name" column.
### Compiling, Training, and Evaluating the Model
- I had two hidden layers in my model with the first layer having 8 neurons and the second layer having 5 neurons. There is also an output layer with the sigmoid activation. <img width="805" alt="Screen Shot 2022-08-10 at 3 49 46 PM" src="https://user-images.githubusercontent.com/100726716/184007174-508d6a1b-e85f-4190-95b7-8d0d5b754fea.png">
- The model was not able to achieve the 75% accuracy level. My model ended with 70% accuracy. <img width="632" alt="Screen Shot 2022-08-10 at 3 51 15 PM" src="https://user-images.githubusercontent.com/100726716/184007369-b5227320-4004-480d-bc4c-70c182e779e1.png">
