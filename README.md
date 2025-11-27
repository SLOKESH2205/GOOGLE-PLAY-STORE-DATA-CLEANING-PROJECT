GOOGLE PLAY STORE DATA CLEANING PROJECT
This project focuses on cleaning and preparing a real-world dataset collected from the Google Play Store. App data is often messy, inconsistent, and noisy. The goal of this work is to transform the dataset into a high-quality, analysis-ready form for future data science and machine learning tasks.

**OBJECTIVES OF THE PROJECT**
Identify and handle missing, incorrect, or inconsistent values
Convert important features to proper data types
Clean and standardize categorical and numerical data
Remove duplicate or invalid app entries
Improve dataset usability for further analysis, visualization or ML model training

**DATASET DESCRIPTION**
The dataset contains information related to Android apps including:
App name
Category
Rating
Reviews
Installs
Size
Type (Free or Paid)
Price
Content Rating
Genres
Last Updated
Current Version
Android Version

**KEY CLEANING STEPS APPLIED**
Removed duplicate app records to maintain unique entries
Converted Reviews, Installs, and Price from strings to numeric format
Cleaned symbol-based values like “1M+”, “500k”, “₹99”, “$0.99” into usable numbers
Processed Size column by converting KB/MB formats into a single MB scale
Replaced invalid entries such as Rating values beyond the 0–5 range
Handled missing values using standard techniques or removal when necessary
Standardized text features and removed unwanted characters where needed
Cleaned inconsistent expressions such as “Varies with device”
Converted Last Updated column into a proper datetime format
Extracted additional time-based features such as Year Updated for advanced usage

**TOOLS AND LIBRARIES USED**
Python
Pandas for data manipulation
NumPy for numerical cleaning
Matplotlib/Seaborn for validation checks (if required later)

**RESULT OF CLEANING PROCESS**
All data columns standardized and correctly typed
Meaningful numeric conversions to enable ML algorithms
Final dataset with better consistency, integrity, and usability
Enhanced reliability for insights and modeling
