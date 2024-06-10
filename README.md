# Goal:

My goal for this project is to create a dashboard in Tableau for Austin shelter trends.

# Methodology:

The dataset is taken from Kaggle. For setup, I wanted to avoid doing any data preprocessing using excel. The raw .csv files were uploaded to MySQL. All editing will be done through custom SQL querires on the data page on Tableau. 

Importing / Cleaning:

First look at the data created some issues. For starters, the column Age Upon Income had an unreadable character at the begining of it. Also, the format for that column has a mix of weeks, months, and years. I would have to change that to ease in formatting. 

Second, the Breed column allows for mixes. This is not a problem at the moment, but  I believe graphing would go easier if we could offer more granularity for looking at the breeds. Same goes for the Color column. 

Last, the .csv formatting for time is unusual. I know that Tableau struggles with weird date formats, so I am going to split the MM/dd/yyyy hh:mm into separate columns. I also am going to remove the time portion of the Date of Birth column since that appears to always be defaulted to 0:00. 
# Deliverable:
# Issues / Credits:

https://www.kaggle.com/datasets/aaronschlegel/austin-animal-center-shelter-outcomes-and
