# Group13_GunControl
-  Team members:
    - Mayank Mishra
    -  Zixiao Wang
    -   Evan Swett
    
- Question(s) sought to answer
   - The primary goal of this project is to examine the efficacy of relevant gun control laws by examining the number of violent gun incidents, injuries and deaths comparatively with the degree of gun control laws in the state at the time of the incidents.
  
  - Predict violent gun incident rates based on laws in state. 

- Data preparation work
  - Data Cleaning/PreProcessing
    - Drop NAs (features with significant NA values).
    - Drop repeated incidents (tricky because difficult to identify unique incidents)
    - One-Hot Encode Categorical features in violent incident dataset
    - Clean nested features within single columns of violent incident dataset.

  - Data Integration
    - The first step in investigating each feature is merging the datasets by their respective keys
    - Adding new features by year and state and population such that we have a metric for understanding the progression of gun violence per capita by state. 

- Tools used
  - Jupyter Notebooks
    - All cleaning, integration, analysis and result visualization will be done using Jupyter Notebooks
      - Pandas, Numpy, Sklearn, SciPy
  - Google Drive
    - All documentation will be saved within a shared folder
  - Zoom
    - Weekly and ad hoc meetings will be conducted via zoom
  - Overleaf
    - Online Latex editor

- Classification/clustering/etc applied,
  - Linear Regression
  - Tried continuous and binned target variables
  - 10 most highly correlated features to serve as predictors
  - Entire law dataset used as predictors
  - Average accuracy of about 60%

- Knowledge gained
  - Men are more likely to die due to gun violence at a rate of 4.5 times than women.  
  - Victims: 10 adults to 1 teen, 2 teens to 1 child. All the age groups follow the same distribution.
  - Gun violence is related to the population, but local culture also taking a strong effect. (For ex,  Illinois, the 6th most populous, has the highest        amount of gun violence. )
  - Distribution of normalized target variables shows negative correlations
  - No strong correlations with gun laws in general

● How that knowledge can be applied.
  - Rising gun violence in the US is an epidemic and therefore should be treated like one
  - Vote in all elections
  - Urge your state government to report all violent deaths to the National Violent Death Reporting System
  - Think critically about where you are receiving your information
