# Diamond-Price-Prediction
This project focuses on predicting the price of diamonds based on their characteristics such as carat, size, and color. The dataset was analyzed using statistical techniques to gain insights into the relationships between variables.

# Statistical Analysis
The statistical analysis of quantitative variables revealed strong positive correlations among the carat, x, y, and z variables, as well as with the price. On the other hand, the depth and table variables showed weak negative correlations with the price. This suggests that carat, x, y, and z can be important predictors of price, while depth and table may have less significance.

The statistical analysis of qualitative variables showed no significant difference in average prices among the different categories of the cut, color, and clarity variables. This implies that these qualitative variables have little impact on diamond prices.

Overall, it is important to consider both quantitative and qualitative variables when evaluating diamond prices. Carat, x, y, and z variables may be important predictors of price, while qualitative variables have minimal impact. It is important to note that other factors, such as diamond rarity and overall quality, can also influence the price. For this project, we will focus on 'carat' and 'y' as the analysis indicated that 'x', 'y', and 'z' variables have minimal differences among them. Random forest regression has shown to provide better results.

# Conclusion
In conclusion, this project aimed to predict the price of diamonds based on their characteristics, including carat, size, and color. An exploratory data analysis was conducted to understand the relationships between variables and identify missing values. Both quantitative and qualitative statistical analyses were performed.

Three regression algorithms, namely linear regression, gradient descent, and random forest regression, were utilized. Random forest regression yielded the best performance with a prediction accuracy of 89.3%. Linear regression achieved a prediction accuracy of 85%. Gradient descent was explored in its classic, optimal step, and stochastic forms, with classic gradient descent converging faster than stochastic gradient descent.

The predictions of linear regression and random forest regression were compared against the actual values in the dataset. It was observed that random forest regression provided more accurate results than linear regression.

In conclusion, random forest regression proved to be the most effective prediction algorithm for this dataset, achieving high accuracy in predicting diamond prices. However, it is important to be aware of the limitations and potential biases of any modeling method and to continue exploring other options as necessary.
