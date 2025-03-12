This project predicts housing prices in Ireland using predictive analytics and machine learning. The analysis includes data preprocessing, feature engineering, and building multiple machine-learning models to achieve accurate predictions. The primary focus is understanding the relationships between property features and their impact on price.

Features of the Dataset ID: Unique identifier for each property. Property Scope: Type of property (e.g., constructed space, land parcel). Availability: Indicates readiness to move or move-in dates. Location: Geographic distribution (e.g., Dublin City Centre, South Dublin). Size: Number of bedrooms. Total Square Feet: Property area in square feet. Bath: Number of bathrooms. Balcony: Number of balconies. BER: Building Energy Rating (A-G). Renovation Needed: Indicates if renovation is required. Price per Sqft ($): Price per square foot in USD. Project Workflow

Exploratory Data Analysis (EDA): Identified trends, patterns, and outliers. Correlation heatmaps and boxplots were used to visualize relationships.

Data Preprocessing: Missing values are imputed using KNN and mode strategies. Categorical variables are encoded using One-Hot and Ordinal Encoding. Outliers are handled with the Interquartile Range (IQR) method. Created a "Price" column for total property value.

Feature Engineering: Converted features like "Size" and "total_sqft" into usable numeric formats. Applied dimensionality reduction using PCA to retain 95% variance.

Predictive Modelling: Models used: Linear Regression, Lasso Regression, Ridge Regression, Decision Tree, Random Forest, Gradient Boosting, and XGBoost. Hyperparameter tuning was conducted via RandomizedSearchCV. Stacking Regressor combined the strengths of multiple models for enhanced performance.
