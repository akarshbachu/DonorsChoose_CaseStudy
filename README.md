# Donors Choose Application Screening
Its a Classification problem, Where we need to classify if the Project proposal can be Approved or not.
# Introduction
#### About DonorsChoose:<br>

Founded in 2000 by a high school teacher in the Bronx, DonorsChoose.org empowers public school teachers from across the country to request much-needed materials and experiences for their students. At any given time, there are thousands of classroom requests that can be brought to life with a gift of any amount.

#### Objective:<br>

The goal of the competition is to predict whether or not a DonorsChoose.org project proposal submitted by a teacher will be approved, using the text of project descriptions as well as additional metadata about the project, teacher, and school. DonorsChoose.org can then use this information to identify projects most likely to need further review before approval.

# About Data
The dataset contains information from teachers' project applications to DonorsChoose.org including teacher attributes, school attributes, and the project proposals including application essays.

#### Files:<br>
Data is provided in Two Files:<br>
<ul>
    <li>train.csv - the training set</li>
    <li>resources.csv - resources requested by each proposal; joins with train.csv on id</li>
</ul>



# About Code

## Data Science
Tried to get some insights of data and Visualized.

Note: Primary focus of this Case Study is getting Good AUC, so focused on Machine Learning part than Data Science part.

## Machine Learning
I have used Two models:
<ul>
    <li>Light GBM with GBDT - LogLoss</li>
    <li>XGBoost with LogLoss</li>
</ul>

Validation Metric Used: AUC

#### Best AUC achieved so far is 0.74 i.e 74% with Light GBM, Check the code in iPython Notebook.


Note: Work in Progress.
