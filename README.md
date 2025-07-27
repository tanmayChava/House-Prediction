# House-Prediction
This project uses a dataset of house sales to predict home prices based on features like square footage, number of bedrooms/bathrooms, location, and more. 
---

1. **Linear Regression** – a baseline model
2. **Random Forest Regressor** – ensemble of decision trees
3. **XGBoost Regressor** – gradient boosting for high performance

## 📁 Dataset Overview

The dataset contains the following columns:

| Feature         | Description                                |
|-----------------|--------------------------------------------|
| date            | Sale date                                  |
| price           | House price (target)                       |
| bedrooms        | Number of bedrooms                         |
| bathrooms       | Number of bathrooms                        |
| sqft_living     | Living area (sq ft)                        |
| sqft_lot        | Lot area (sq ft)                           |
| floors          | Number of floors                           |
| waterfront      | Waterfront view (0 or 1)                   |
| view            | Quality of view (0–4)                      |
| condition       | Overall condition (1–5)                    |
| sqft_above      | Area above ground                          |
| sqft_basement   | Basement area                              |
| yr_built        | Year built                                 |
| yr_renovated    | Year renovated (0 if never)                |
| street          | Street address (categorical)               |
| city            | City (categorical)                         |
| statezip        | State and ZIP code (categorical)           |
| country         | Country (categorical)                      |
