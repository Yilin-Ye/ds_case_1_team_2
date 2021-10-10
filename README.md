# Hospital Ward Admission Calculation

### Contributors: Connor Mignone, Amanda Konet, Yilin Ye, Tonnar Castellano, Sarah Torrence

## Project Description
This project is based on a [Kaggle post](https://www.kaggle.com/einsteindata4u/covid19/version/7) post by the Hospital Israelita Albert Einstein in Sao Paulo, Brazil in the height of the covid-19 pandemic. In 2020 Brazil recorded its first confirmed case of COVID-19. Since then the state
of Sao Paulo has recorded over 1,200 cases of covid with nearly 70 deaths. Nearly a third of
these cases were located in the county of Sao Paulo where the Hospital Israelita Albert Einstein
resides. To combat the devastating effects of COVID-19 Hospital Israelita Albert Einstein wants
to leverage [data](https://www.kaggle.com/einsteindata4u/covid19) to try and perform the following two tasks:
1) Predict who will test positive for covid-19.
2) Predict who will go into the ICU, semi-intensive unit, general ward or be dischagred among covid-19 positive patients. 

We chose to focus on the second task of predicting which ward a covid positive patient will be admitted into.

## Directory 
Here you can find a directory to all the files within our repo that were used in performing our analysis.

### [Data](https://github.com/Yilin-Ye/ds_case_1_team_2/tree/main/data)
This folder contains all the various data both rough and final including but not limited to [groupings](https://github.com/Yilin-Ye/ds_case_1_team_2/tree/main/data/feature_groups) and the final [ROSE/Smote](https://github.com/Yilin-Ye/ds_case_1_team_2/tree/main/data/final) Data.

### [Data Dictionary](https://github.com/Yilin-Ye/ds_case_1_team_2/tree/main/Data%20dictionary)
This folder contains a data dictionary which include explanations for each variable. 

### [Data Cleaning Eng](https://github.com/Yilin-Ye/ds_case_1_team_2/tree/main/data_cleaning_eng)
This folder contains the code that we ran as a combined effort of all our individual cleaning tasks. This code creates the original cleaned data set before any resampling methods are applied. 

### [EDA](https://github.com/Yilin-Ye/ds_case_1_team_2/tree/main/eda)
This folder contains the various efforts to explore the data such as lab test groupings and graphics.

### [Modeling](https://github.com/Yilin-Ye/ds_case_1_team_2/tree/main/modeling) 
This folder contains the code for the random forest and k nearest neighboors models. The modeling.rmd file is the final modeling file. 

## Results

You can see details of our methods as well as final approach in our presentation, but to summarize we found the best model was a random forest model using Rose sampling and 5-fold cross validation with the following confusion matrix and test results. 

<img width="359" alt="image" src="https://user-images.githubusercontent.com/69755309/136696301-dd329f30-daca-493d-9ff8-f58e50f156fd.png">

<img width="323" alt="image" src="https://user-images.githubusercontent.com/69755309/136696329-979e6c13-6fbd-45c5-92a9-876d8e607b15.png">

