This project successfully applied Linear Regression to predict Sales based on advertising spend across TV, Radio, and Newspaper channels.

🔹 Simple Linear Regression (Sales ~ TV)

Equation: Sales = 9.70 + 0.0357 × TV

R² = 0.373, MAE = 2.96, RMSE = 3.68

Interpretation: TV advertising alone explains ~37 % of sales variation. Increasing TV spend by $1 k raises expected sales by about $36.

🔹 Multiple Linear Regression (Sales ~ TV + Radio + Newspaper)

Equation: Sales = 3.45 + 0.0412 × TV + 0.1945 × Radio + 0.0175 × Newspaper

R² = 0.810, MAE = 1.67, RMSE = 2.02

Interpretation: When all media channels are combined, the model explains ~81 % of the variation in sales.
Radio has the strongest effect on sales, followed by TV, then Newspaper.

Visual Insights

Sales vs TV Regression Plot: Shows a clear positive relationship.

Actual vs Predicted Sales Plot: Most points lie close to the diagonal line, confirming strong predictive accuracy.

Conclusion

The linear-regression model accurately captures how advertising investments influence sales performance.
The results demonstrate that diversified ad spending (especially on TV + Radio) yields the highest impact on sales.
This fulfills the task objective of building, training, and evaluating a regression model using a simple, real-world-style dataset.
