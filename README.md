# Neural Network
Build own machine learning model to predict success of a venture paid by Alphabet Soup.  What is their likelihood of success?


# Resources
Data Source: charity_data.csv Software: Python 3.6.1, Jupyter Notebook 6.0.1, tensorflow, Scikit-learn


# Challenge Results
- Import charity_data to create starting dataframe to clean and pre-process the data.  Based on the variables provided, had to select which ones are targets and features to answer the Challenge quesiton.
- For example created a shared index with column EIN between the cleaned dataframes that will be merged
- Separated out the IS SUCCESSFUL column as the target variables
- Counted unique values for columns such as Application and Classification that had a lot of values that needed to be grouped into smaller bins
(Visualized what the distribution looked like for these columns)
![binning](https://github.com/shumeiberk/Neural_Network/blob/main/images/binning.PNG)

- Played around with neural network model on the different layers as well as different epochs (100,80, 50)
- Used ReLU activation as the first layer and sigmoid as the output layer
- best accuracy achieved was 53% with loss of 70%, was below the targeted goal of 75%
![accuracy](https://github.com/shumeiberk/Neural_Network/blob/main/images/accuracy.PNG)

