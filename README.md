In task 2 we've done data cleaning, preprocessing and visualizing which can be summarized as follows :

1. **Data Cleaning** :
   - **Reading Data** : The dataset was read into a pandas DataFrame.
   - **Handling Null Values** : Null values were identified and either removed or replaced with appropriate values such as mean or median.
   - **Invalid Data Types** : Data types were corrected to ensure proper analysis 
   - **Categorization** : Data was categorized into numerical and categorical types.
   - **Outliers** : Outliers were detected and removed 
   - **Duplicates** : Duplicate values were identified and removed.

2. **Preprocessing** :
   - **Normalization** : Numerical data was normalized using SimpleImputer
   - **Encoding Categorical Data** : Categorical variables were encoded using one-hot encoding

3. **Visualization** :
   - **Correlation Analysis** : Heatmaps were used to visualize correlations between variables.
   - **Trends and Patterns** : scatter plots were used to identify trends and patterns in the data.
   -  **Categorical Data Visualization** : Bar charts and count plots were used to visualize categorical data.

The following conclusions can be taken after visualizing the data : 
   - There is a high positive corelation between :
      - attacking_short_passing and skill_ball_control (age plays a role)
      - mentality_positioning and attacking_finishing
      - skill_dribbling and attacking_finishing
      - variables like cam, cdm, lw, etc..
  - Most of the people in the dataset belong from countries like *spain*, *Brazil* and *France*
- A Majority of the people prefer to play with right foot 
