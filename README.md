## **Stock Price Prediction with Sentiment Analysis**  

![Stock Prediction](https://cdn.analyticsvidhya.com/wp-content/uploads/2021/07/21894download.jpg)  

### Overview  
This project predicts stock prices using **LSTM (Long Short-Term Memory) networks** and incorporates **sentiment analysis** on financial news to improve accuracy.  

**Key Features:**  
 Fetches stock price data using Yahoo Finance  
 Performs sentiment analysis on financial news using NLP  
 Uses LSTM to predict future stock prices based on past trends  

---

## Project Structure
```
   stock-price-prediction-sentiment
 ┣ README.md                 # Project documentation
 ┣ requirements.txt          # Dependencies list
 ┗ main.py                   # Main script to run the project
```

---

## Installation
Follow these steps to set up the project on your local machine.  

### 1️ Clone the Repository
```sh
git clone https://github.com/manasak-12/Stock-Price-Pridiction-with-LSTM-and-Sentiment-analysis
cd stock-price-prediction-sentiment
```

### 2️ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️ Run the Project 
  ```
  python main.py
  ```

---

##  Data Sources
- **Stock Price Data**: Retrieved from [Yahoo Finance](https://finance.yahoo.com/) using the `yfinance` library.  
- **Financial News Data**: Used for sentiment analysis, sourced from news APIs or manually inputted CSV files.

---

##  Methodology
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

##  Dependencies
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

##  Future Improvements
-  Add more financial news sources for better sentiment accuracy.  
-  Implement attention mechanisms in LSTM models.  
-  Deploy the model as a web application using Flask or FastAPI.  

---

##  Author
**Anagha V**  
**K Manasa**  
**Prasad**  
 Email: anagha6393@gmail.com    GitHub: [github.com/anagha-2538](https://github.com/anagha-2538)<br>
 Email: manasakumar1209@gmail.com    GitHub: [github.com/manasak-12](https://github.com/manasak-12)<br>
 Email: prasad.u.patil.2004@gmail.com   Github: [github.com/Prasad2004Patil](https://github.com/Prasad2004Patil)<br

---
