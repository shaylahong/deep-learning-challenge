# deep-learning-challenge

Analysis

Results: 

1. Data Preprocessing 

    - What variable(s) are the target(s) for your model? 
    y = numeric_df["IS_SUCCESSFUL"].values 

    - What variable(s) are the features for your model? 
    X = numeric_df.drop(["IS_SUCCESSFUL"],1).values 

    - What variable(s) should be removed from the input data because they are neither targets nor features?
    application_df = application_df.drop(columns=["EIN","NAME"])

