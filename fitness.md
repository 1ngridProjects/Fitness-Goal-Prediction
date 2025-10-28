Fitness and Workout Data Analysis & Goal Prediction

Project Overview
    This project explores a dataset of workout and fitness programs to uncover patterns, trends, and relationships across workout  levels, goals. and equipment.

    It also includes a machine learning component that predicts a program's goal based on its structure and difficulty.

Project Structure
    Cleaned and structured dataset columns
    Converted stringified lists into Python lists
    Filled missing values, parsed dates, and standardized text.

    Descriptive statistics:
        Count of programs by Goal, Level, and Equipment 
        Distribution of program length, time per workout, and total exercises

    Visualizations:
        Bar charts of levels, goals, and equipment types
        Correlation heatmap for numeric features
        Boxplots of programmetrics by level 
        Timeline trend of program creation dates
        Pairplot to show features relationships

    Machine Learning: Predicting Workout Goal
        Predict a program's main goal using key features:
            program legnth
            time per workout
            total exercises
            main level
        
        Feature engineering: extracted main_level and main_goal as simplified categories

        Encoding and scaling:
            Used OneHotEncoder for categorical features
            Used StandardScaler for numeric features.

        Train/test split (80/20 stratfied)

        Models trained:
            Logistic Regression
            Random Forest Classifier

        Evaluation:
            Metrics used:
                Accuracy
                F1-Score
                Confucsion Matrix Visualization
    
    Feature Importance:
        Top predictors for workout goal (Random Forest):
            Program Length
            Level
            Time per workout
            Total Exercises

  