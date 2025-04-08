# NHL-MVP-Prediction

- Data sourced from [moneypuck.com](https://moneypuck.com/data.htm)

<br>

- Using [scikit-learn linear regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html) and [pandas](https://pandas.pydata.org).

<br>

- Using various NHL skater-only features to predict an MVP for a season.
- Features include games played, points, points per game, etc.
- Data used ranges from 2015-2023.

<br>

- Predictions are made using an entire season's data.
- The output is the top 10 most likely MVP candidates for a given season.
- Summary statistics include MSE and feature importance.

<br>

## Visualizations
### MVP Total Points Breakdown by Season
![alt text](./images/image.png)

### MVP Points-Per-Game by Season
![alt text](./images/image-1.png)

### Top 10 MVP Predictions for 2023-2024
- Nathan MacKinnon had won the award this season.

![alt text](./images/image-2.png)

### Feature Importance
- The percentage of all team goals a player was the ice for and their points per game were the most impactful in the regression model.

![alt text](./images/image-3.png)