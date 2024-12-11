


This project focuses on predicting Bitcoin prices using historical data retrieved from CryptoCompare, a leading cryptocurrency data aggregator. The prediction models are built using two machine learning algorithms: Long Short-Term Memory (LSTM) and Random Forest. The project utilizes the last 365 days of Bitcoin price data, which is processed and transformed into a Pandas DataFrame for analysis. The 'close' prices are scaled using the Min-Max Scaler to optimize model training. The LSTM model, being highly effective in capturing long-term dependencies in time-series data, is applied for forecasting Bitcoin price trends. Meanwhile, the Random Forest algorithm is employed to offer a robust and accurate prediction by combining multiple decision trees. By evaluating the models' predictive accuracy, with LSTM achieving 97.88% and Random Forest achieving 94.65%, this project highlights the performance and effectiveness of different machine learning techniques in forecasting Bitcoin prices.

Algorithms Used:
Long Short-Term Memory (LSTM):

LSTM is a type of recurrent neural network (RNN) designed for time-series forecasting. It is well-suited for capturing long-term dependencies in sequential data, such as Bitcoin price trends over time. LSTM can effectively handle issues related to vanishing gradients, allowing it to predict Bitcoin prices based on past trends.
Random Forest:

Random Forest is an ensemble learning method that builds multiple decision trees and combines their predictions for improved accuracy. It works well with high-dimensional data and is less prone to overfitting. In this project, Random Forest helps to provide robust predictions of Bitcoin prices by aggregating predictions from several decision trees, ensuring higher accuracy.
Advantages:
High Predictive Accuracy:

The LSTM model achieved a predictive accuracy of 97.88%, and the Random Forest model reached 94.65%. This demonstrates the strong potential of machine learning models in providing accurate forecasts for Bitcoin prices, assisting traders and investors in making informed decisions.
Time-Series Analysis:

The use of LSTM allows the model to effectively capture and learn from long-term dependencies in Bitcoin's price trends, which is crucial for time-series forecasting in volatile markets like cryptocurrency.
Robustness of Random Forest:

Random Forest's ensemble approach ensures that the model is not overly reliant on a single decision tree, making it more resilient to fluctuations and noise in the data, thus improving overall prediction accuracy.
Real-Time Data Utilization:

By using real-time historical Bitcoin price data from CryptoCompare, the models are trained on up-to-date information, ensuring that the predictions reflect the current market trends and conditions.
Data Preprocessing for Optimal Performance:

The data is preprocessed and split into training and testing sets, which ensures that the models are evaluated on unseen data, providing a realistic estimate of their generalization performance.
Scalable for Future Data:

The models can be easily updated with new data, allowing for continuous improvement and adaptation to changing market conditions, making them scalable for future Bitcoin price predictions.
This project showcases the potential of using machine learning techniques like LSTM and Random Forest for accurate Bitcoin price prediction, providing valuable insights for the cryptocurrency market.






