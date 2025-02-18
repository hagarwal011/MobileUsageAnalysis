# MobileUsageAnalysis

## **Project Overview:**

1. **Dataset Processing:**
    - **Task:** Download the dataset and upload it to Google Drive for further processing.
    - **Requirements:**
        - Download the dataset from the provided link.
        - Upload the dataset to Google Drive for accessibility.
        - Connect to Google Drive using Python to access the dataset programmatically.
        - Load the dataset into a pandas DataFrame and clean the data (e.g., handle missing values, normalize fields).
        - Prepare the cleaned data for further analysis.
2. **Data Analysis & Visualization:**
    - **Task:** Perform exploratory data analysis (EDA) to identify usage patterns and user behaviors.
    - **Requirements:**
        - Analyze the dataset to identify trends, such as:
            - Average screen time of users.
            - Most commonly used apps.
            - Usage patterns based on user demographics (e.g., age, gender).
            - Time-of-day usage patterns.
        - Create visualizations such as bar charts, histograms, line graphs, pie charts, and heatmaps to represent the findings.
        - Use Python libraries like Matplotlib, Seaborn, and Plotly for visualizations.
3. **User Segmentation(Optional):**
    - **Task:** Segment users based on their behavior.
    - **Requirements:**
        - Perform clustering (e.g., K-means, DBSCAN) to group users with similar usage patterns.
        - Analyze the characteristics of each segment, such as average screen time, most used apps, and active hours.
        - Visualize the clusters using scatter plots or 3D plots to provide a clear understanding of the user segments.
4. **Insights & Predictions(Optional):**
    - **Task:** Provide key insights based on the analysis.
    - **Requirements:**
        - Identify key factors affecting mobile device usage, such as time spent on different apps, user activity patterns, etc.
        - Build a simple predictive model to predict a user’s behavior (e.g., predicting screen time or app usage based on demographics).
        - Evaluate the model performance using appropriate metrics like accuracy, precision, recall, or RMSE (Root Mean Squared Error).
5. **SQL Database Integration:**
    - **Task:** Load the cleaned data into an SQL database for storage and future querying.
    - **Requirements:**
        - Set up an SQL database and create tables to store the cleaned data.
        - Use Python to load the cleaned data from pandas into the SQL database.
        - Perform queries to analyze user behavior, such as total screen time per user group, most active app categories, etc.
6. **Power BI:**
    - **Task:** Create a dynamic Power BI dashboard based on your analysis.
    - **Requirements:**
        - Load your dataset into Power BI and create visualizations based on the insights.
        - Ensure the dashboard includes key metrics such as average screen time, most active users, and user segmentation.
        - Make the dashboard interactive and visually appealing.
