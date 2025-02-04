## **Stock Price Prediction with Sentiment Analysis**  

![Stock Prediction](https://upload.wikimedia.org/wikipedia/commons/3/3a/Stock_Market_Investments.jpg)  

### **Overview**  
This project predicts stock prices using **LSTM (Long Short-Term Memory) networks** and incorporates **sentiment analysis** on financial news to improve accuracy.  

**Key Features:**  
✅ Fetches stock price data using Yahoo Finance 📈  
✅ Performs sentiment analysis on financial news using NLP 📊  
✅ Uses LSTM to predict future stock prices based on past trends 📉  

---

## **📂 Project Structure**
```
📦 stock-price-prediction-sentiment
 ┣ data                      # Stores raw data
 ┣ README.md                 # Project documentation
 ┣ requirements.txt          # Dependencies list
 ┗ main.py                   # Main script to run the project
```

---

## ** Installation**
Follow these steps to set up the project on your local machine.  

### **1️ Clone the Repository**
```sh
git clone https://github.com/YOUR_USERNAME/stock-price-prediction-sentiment.git
cd stock-price-prediction-sentiment
```

### **2️ Install Dependencies**
```sh
pip install -r requirements.txt
```

### **3️ Run the Project**
- **Preprocess the data**  
  ```sh
  python src/preprocess.py
  ```
- **Train the model**  
  ```sh
  python src/train_model.py
  ```
- **Make predictions**  
  ```sh
  python src/predict.py
  ```

---

## ** Data Sources**
- **Stock Price Data**: Retrieved from [Yahoo Finance](https://finance.yahoo.com/) using the `yfinance` library.  
- **Financial News Data**: Used for sentiment analysis, sourced from news APIs or manually inputted CSV files.

---

## ** Methodology**
1. **Data Collection**  
   - Fetch stock price data (Open, Close, High, Low, Volume).  
   - Collect financial news headlines for sentiment analysis.  

2. **Sentiment Analysis (NLP)**  
   - Uses `nltk`’s **VADER** (Valence Aware Dictionary and sEntiment Reasoner).  
   - Assigns sentiment scores to news articles.  

3. **LSTM Model Training**  
   - Processes stock prices & sentiment scores.  
   - Uses LSTM layers for time-series forecasting.  

4. **Prediction**  
   - Uses trained LSTM model to predict future stock prices.  

---

## ** Example Output**
```sh
Data preprocessing complete!
Model training complete!
Predicted Stock Price: 152.75
```

---

## **📋 Dependencies**
```txt
numpy
pandas
matplotlib
tensorflow
keras
sklearn
nltk
yfinance
```

## ** Future Improvements**
-  Add more financial news sources for better sentiment accuracy.  
-  Implement attention mechanisms in LSTM models.  
-  Deploy the model as a web application using Flask or FastAPI.  

---

## ** Author**
**[Anagha V]**  
**[K Manasa]**  
**[Prasad]**  
📧 Email: your.email@example.com  
🔗 GitHub: [github.com/manasak-12](https://github.com/manasak-12)  

---
