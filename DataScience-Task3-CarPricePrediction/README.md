# Car Price Prediction with Machine Learning

## Oasis Infobyte Data Science Internship – Task 3

### Objective
Build a machine learning regression model to predict the selling price of used cars based on relevant features such as brand, age, mileage, fuel type, transmission, and other available attributes.

### Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

### Project Steps
- Loaded and cleaned the used car dataset
- Removed duplicate records
- Standardized categorical values
- Calculated car age from the manufacturing year
- Extracted car brand from the car name
- Performed exploratory data analysis
- Encoded categorical variables
- Created a correlation heatmap
- Split the data into training and testing sets
- Trained Linear Regression and Random Forest Regressor models
- Evaluated models using MAE, RMSE, and R²
- Compared model performance
- Created a feature importance chart for the Random Forest model

### Model Performance

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Linear Regression | 176948.26 | 385996.62 | 0.5375 |
| Random Forest | 135965.97 | 359121.28 | 0.5996 |

### Best Model
The **Random Forest Regressor** performed better than Linear Regression, with lower MAE and RMSE and a higher R² score.

### Files
- `Car_Price_Prediction.ipynb` – Complete Jupyter Notebook
- `CAR DETAILS FROM CAR DEKHO.csv` – Dataset
- `README.md` – Project documentation

### Internship
**Oasis Infobyte – Data Science Internship**  
**Task 3: Car Price Prediction with Machine Learning**
