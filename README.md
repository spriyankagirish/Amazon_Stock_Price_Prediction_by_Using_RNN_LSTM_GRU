### Amazon Stock Price Prediction using RNN, GRU, and LSTM

### Project Description:
This project focuses on predicting Amazon's stock prices using time-series deep learning models such as Recurrent Neural Networks (RNN), Gated Recurrent Units (GRU), and Long Short-Term Memory (LSTM). Stock price prediction is an essential component in the financial industry, where historical price data and other features are used to forecast future movements. These models are particularly suited to capturing patterns in sequential data and are leveraged here to predict future stock prices based on historical trends.

### Objectives:
1. **Data Collection and Preparation**: 
   - Collect historical stock price data for Amazon (AMZN) over a specified time period. 
   - Features include Open, High, Low, Close prices, Volume, and other stock-related data.
   
2. **Data Preprocessing**:
   - Handle missing values, outliers, and anomalies in the dataset.
   - Normalize/scale the data to optimize model performance.
   - Split the dataset into training, validation, and test sets to evaluate model accuracy.

3. **Model Implementation**:
   - **RNN**: A basic Recurrent Neural Network model is implemented to capture the sequential dependencies in the stock prices.
   - **GRU**: Gated Recurrent Units, a more advanced RNN variant, is implemented to reduce the vanishing gradient problem and improve long-term dependency handling.
   - **LSTM**: Long Short-Term Memory networks are used to handle both short- and long-term dependencies in the time-series data and capture complex stock price movement patterns.
   
4. **Model Evaluation**:
   - Evaluate the performance of each model using error metrics such as Mean Squared Error (MSE) and Mean Absolute Error (MAE).
   - Compare the results of RNN, GRU, and LSTM models to determine which provides the best predictions.

5. **Prediction and Visualization**:
   - Use the trained models to predict future stock prices of Amazon.
   - Visualize the predicted stock prices against the actual stock prices to evaluate performance.
   - Provide insights based on model predictions.

### Conclusion:
This project demonstrates the use of deep learning techniques such as RNN, GRU, and LSTM for time-series forecasting, specifically in the context of stock price prediction. Among the models, **LSTM** tends to outperform the basic RNN and GRU in terms of accuracy due to its ability to manage both short-term and long-term dependencies in sequential data. However, each model has its strengths and trade-offs in terms of complexity and training time.

 ---

### Note on Dataset Access

To maintain data privacy and prevent misuse, the dataset used in this project is not uploaded directly to this repository.

**If you're a recruiter  who would like to access the dataset**, please request access here: https://drive.google.com/drive/folders/1zqHP1-UkiJP_lRE74WBLz6-oKJCqylZf?usp=sharin

Once approved, you’ll receive a link to the dataset via Google Drive within 24 hours.

*This ensures project security while keeping it fully reproducible.*



# Dataset not included in the public repo

# Please request access using the link in the README to get the dataset

