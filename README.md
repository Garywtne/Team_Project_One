# Which factors contribute to accident risk?
![Title Image](readme_images/title.jpg)

### Contents
1. Dataset
2. Explanation
3. Examplot plots
4. Dependencies Required
5. How to view / run the code
6. Which Jupyter notebooks


### Choosing a dataset
We used the UK Road Safety: Traffic Accidents and Vehicles\
Detailed dataset of road accidents and involved vehicles in the UK (2005-2017).\
Availble from Kaggle.com

There are 2 CSV files in this data set. Both CSV files were merged into a single dataframe. The resulting data file extremely large so a decision was made to focus on Years 2010-2016. This data was filtered and placed into a New CSV which is the main data used for all the investigation, analysis and plots.

We decided our client question would be **"which factors contribute to accident risk?"** and used this question to formulate 4 hypotheses and used these to target the data relevant to our hypotheses and attempt to turn that raw data in to **meaningful information**.

### Hypothesis 1: Younger drivers are involved in more accidents
### Hypothesis 2: Driving on a weekday has no affect on the number of accidents.
### Hypothesis 3: Higher speed limit increases the number of accidents
### Hypothesis 4: There are more accidents when the weather conditions are bad

For each hypotheses we created a number of visualisations to display the data in an easier to analyse format which helped us understand the information required.

### Example Plots


### Dependencies Required
In order to run the files you will need to install the following packages
* gmaps 'pip install gmaps'
* pandas 
* seaborn
* matplotlib
* scipy
* jupyter

**Add this file into your local cloned repository** It has not been included in the repository due to the large file size.

all.csv (accidents from 2010-2016) - link: 

### Gmaps API Key requirement

For gmaps you will also need an API key from the Google Maps Platform.

The key should be stored in your local repository root folder in a config.py file.


### How to view / run the code
The work was completed primarily using Jupyter Notebooks and the modules listed in the Dependencies section.

* Clone the repository and open the Jupyter Notebook files and run the cells in order.

The Jupyter notebook files have comments in the code and Markdown cells beneath each step explaining what was done.


### Which Jupyter Notebooks
* notebook 1.ipynb
* notebook 2.ipynb
* notebook 3.ipynb

### Where the plot images are stored





### Credits / Collaborators
Gary W\
Jessica Uppal\
Serdar B\
Arshad Sheikh\
Abdurrahman Raja

Add Social badges?