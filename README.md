# Industrial_copper_modelling

**Problem Statement for README:**

**Challenges in the Copper Industry: Leveraging Machine Learning for Optimal Decisions**

The copper industry faces challenges in handling sales and pricing data that may exhibit skewness and noise, impacting the accuracy of manual predictions. Manually addressing these issues is time-consuming and may not yield optimal pricing decisions. To enhance accuracy and efficiency, a solution involving machine learning regression models is proposed. These models leverage advanced techniques like data normalization, feature scaling, and outlier detection, along with robust algorithms tailored for skewed and noisy data.

Another critical concern in the industry is lead capture. Establishing a lead classification model becomes imperative for evaluating and categorizing leads based on their likelihood to convert into customers. The STATUS variable is utilized, with "WON" denoting success and "LOST" indicating failure. Data points with statuses other than "WON" or "LOST" are removed for clarity.

**Solution Framework:**

1. **Data Exploration:**
   - Investigate skewness and identify outliers in the dataset.

2. **Data Transformation and Pre-processing:**
   - Transform the data into a suitable format.
   - Implement necessary cleaning and pre-processing steps to enhance model performance.

3. **Machine Learning Regression Model:**
   - Develop a regression model to predict the continuous variable 'Selling_Price.'
   - Utilize techniques such as data normalization and feature scaling to enhance model accuracy.

4. **Machine Learning Classification Model:**
   - Construct a classification model to predict lead status (WON or LOST).
   - Exclude data points with statuses other than "WON" or "LOST" for focused analysis.

5. **Streamlit Integration:**
   - Create a Streamlit web application interface.
   - Allow users to input values for each column and receive predicted values for Selling_Price or classified lead status (WON/LOST).

This comprehensive solution aims to streamline pricing decisions in the copper industry by leveraging machine learning techniques to handle data complexities and enhance lead classification. The user-friendly Streamlit interface facilitates seamless interaction and decision-making based on predicted Selling_Price and lead status.
