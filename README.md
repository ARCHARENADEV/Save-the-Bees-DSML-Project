# Save-the-Bees-DSML-Project
DSML project using machine learning
Final Project Description
Save the Bees: Long-Term Agricultural Pollinator Dynamics (1980–2024)
Project Overview

This project focuses on analyzing long-term trends in bee populations and understanding how agricultural and environmental factors influence pollinator dynamics. Bees play a crucial role in crop production and ecosystem stability, and recent declines in bee populations have raised global concerns. Using historical data from 1980 to 2024, this project applies Data Science and Machine Learning techniques to study these trends and build a predictive model.

Objective

The main objective of this project is to:

Analyze the relationship between agricultural practices and bee populations.

Identify key environmental and farming factors affecting bee colony counts.

Build a machine learning model to predict the number of bee colonies using historical data.

Dataset Description

The dataset was obtained from Figshare, a trusted open-data repository. It contains multi-year agricultural and environmental data, including:

Year

Cultivated land area

Pesticide usage

Average temperature

Annual rainfall

Crop yield

Agricultural production

Number of bee colonies

This dataset enables long-term trend analysis and predictive modeling.

Methodology

The project followed a complete end-to-end Data Science workflow:

Data Loading:
The dataset was imported into Jupyter Notebook using Python libraries.

Data Preprocessing:

Missing values in numerical columns were handled using mean imputation.

Invalid records (such as zero or negative colony counts) were removed.

Relevant features were selected for modeling.

Exploratory Data Analysis:

Trends in bee populations and agricultural factors were visually examined.

Relationships between variables were analyzed.

Feature Selection:
Key variables influencing bee populations were selected based on domain relevance.

Model Building:
A Linear Regression model was implemented to predict the number of bee colonies.

Model Evaluation:
The model’s performance was evaluated using:

Mean Squared Error (MSE)

R² Score

Results

The trained model demonstrated reasonable predictive performance. The evaluation metrics indicate that agricultural factors such as pesticide usage, cultivated land area, temperature, rainfall, and crop yield have a measurable impact on bee populations. This confirms the usefulness of data-driven approaches in environmental analysis.

Conclusion

This project successfully demonstrates how Data Science and Machine Learning techniques can be applied to environmental and agricultural data. The results highlight the influence of human agricultural practices on pollinator populations and emphasize the importance of sustainable farming. The study also shows that machine learning models can assist in monitoring and predicting ecological trends over time.

Future Scope

Applying advanced models such as Random Forest or XGBoost.

Including geographical analysis using region-wise data.

Integrating real-time environmental data for continuous monitoring.

Tools & Technologies Used

Python

Jupyter Notebook

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

GitHub for version control
