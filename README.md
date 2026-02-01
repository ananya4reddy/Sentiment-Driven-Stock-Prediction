# Market Mood & moves : Sentiment-Driven Stock Prediction

## Overview 
This repository contains my work for the WiDS project Market Mood & Moves: Sentiment-Driven Stock Prediction, completed across Weeks 1 to 4. Through this project, I learned how stock price data, financial news, and sentiment analysis can be connected to study market behavior.

I worked on fetching stock data and news using APIs, analyzing sentiment using NLP models, and learning how time-series models like LSTMs can be used for prediction. In the later stages, I focused on integrating these components into a single pipeline to generate buy, sell, or hold signals. Overall, this repository reflects my learning process, experiments, and understanding developed throughout the course.

### Week 1 
- revised Python programming fundamentals
- Data manipulation with Pandas
- Numerical computing with numpy
- Natural Language Processing Fundamentals and steup
- as a part of text preprocessing , tokenization , stop words removal, lemmatization
- API based data collection using NewsAPI integration, Stock data yfinance
- Sentiment analysis , VADER sentiment analyzer and FinBERT for financial text
- Behavioral finance concepts
- Quantitative finance fundamentals
- attempted Challenges

### Week 2 
- Evolution of embeddings, static and dynamic(BERT)
- Theory behind BERT architecture
- Pretraining objectives like MLM, NSP
- FinBERT domain adaption
- Huggingface Transformers implementation
- attempted Advanced topic challenges

### Week 3 
- Introduction to time-series data in financial markets
- Understanding why stock prices depend on past values
- Basics of sequential modeling for price prediction
- Limitations of traditional models for time-dependent data
- Introduction to Recurrent Neural Networks (RNNs)
- Motivation for using LSTMs over vanilla RNNs
- Understanding LSTM memory cells and gates conceptually
- Sliding window approach for creating input sequences
- Feature engineering for time-series:Daily returns, Volatility, momentum indicators (RSI, MACD)
- PyTorch to build and train LSTM model

### Week 4 
- Integrating sentiment analysis with stock price prediction
- Combining Week 2 (FinBERT) and Week 3 (LSTM) concepts
- End-to-end pipeline design for stock prediction
- Using NewsAPI for real-time financial news
- Using yFinance for OHLCV stock data
- Converting news sentiment into numerical signals
- Feeding combined features into an LSTM-based model
- Generating BUY / SELL / HOLD signals
- Understanding practical limitations of prediction-based trading

### Resources used : 

API based data collection - https://newsapi.org/,  
NLP fundamentals - https://www.nltk.org/book/,  
for revising python - https://www.w3schools.com/python/,  
for Pandas - https://pandas.pydata.org/docs/user_guide/10min.html, https://www.geeksforgeeks.org/pandas-tutorial/,  
for numpy - https://www.w3schools.com/python/numpy/,  
Reading guides by mentors 
http://localhost:8888/lab/tree/week_1/week_1_reading.pdf, 
http://localhost:8888/lab/tree/week_2/week_2_reading.pdf






