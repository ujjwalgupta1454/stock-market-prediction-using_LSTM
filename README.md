# 💰 Stock Market Prediction using LSTM 💸

## Overview
Emphasizes the uniqueness and innovation of the project in providing accurate stock market predictions using LSTM neural networks and real-time data.

## Objective
Utilize advanced machine learning techniques to forecast stock prices with high accuracy, aiding investors in making informed decisions.

## Model Used
In this project, we leverage Long Short-Term Memory (LSTM) neural networks, a type of recurrent neural network (RNN), renowned for capturing long-term dependencies in sequential data like stock prices.

## Technologies & Tools Used
- **Python:** Core language for backend development and ML implementation.
- **TensorFlow and Keras:** Deep learning frameworks for building and training the LSTM model.
- **Pandas:** Data manipulation and preprocessing.
- **Matplotlib and Seaborn:** Visualization of predicted vs. actual stock prices.
- **yfinance library:** Real-time financial data retrieval.

## Project Overview
In this project, we leverage historical stock market data to train an LSTM model. The model learns from past price patterns and trends, enabling it to predict future stock prices. The LSTM network is specifically designed to capture long-term dependencies and has proven to be effective in time series forecasting tasks.

## Dataset
We use a publicly available dataset containing historical stock prices of various companies. The dataset includes features like opening price, closing price, volume, etc. We preprocess the data, splitting it into training and testing sets, and perform any necessary data transformations.

## Model Training
The LSTM model is built using TensorFlow and Keras. We optimize hyperparameters such as the number of hidden layers, neurons per layer, and learning rate. Techniques like regularization and dropout are employed to prevent overfitting.

## Evaluation and Results
Once trained, the model's performance is evaluated on the testing dataset using metrics such as mean squared error (MSE), root mean squared error (RMSE), and mean absolute error (MAE). Visualizations of predicted vs. actual stock prices provide insights into the model's accuracy and reliability.

![Predicted vs. Actual stock prices](https://github.com/ujjwalgupta1454/stock-market-prediction-using_LSTM/blob/main/Results%20Screenshots/Predicted%20vs.%20Actual%20stock%20prices.png)

![Predicted vs. Actual values & F2 Score](https://github.com/ujjwalgupta1454/stock-market-prediction-using_LSTM/blob/main/Results%20Screenshots/Predicted%20vs.%20Actual%20values%20%26%20F2%20Score.png)

### Results and Discussion
We achieved an impressive R2 score of 0.97, demonstrating the model's ability to explain stock price variance. The mean absolute error of 4.63% underscores its reliability in predicting stock movements. Visualizations highlight the model's trend-following ability, aiding in potential financial gains.

## Contributing 
I welcome contributions to enhance the project and make it even more effective. If you have any suggestions, bug fixes, or new features to add, please submit a pull request. I appreciate your contributions!

## Contact
For any questions or inquiries, feel free to reach out to me:
- **Email:** ujjwalgupta1454@gmail.com
- **LinkedIn:** [Ujjwal Gupta](https://www.linkedin.com/in/ujjwal-gupta24/)

Thank you for visiting my project repository.