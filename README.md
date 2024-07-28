# 📊 Short Term Stock Market Prediction System Using Machine Learning Techniques🌟

Welcome to the **Short Term Stock Market Prediction System Using Machine Learning Techniques**! 🚀 This project is designed to assist users in making smarter investment decisions by predicting the closing stock prices of companies across different investment horizons: short-term 📅 (1-2 days), mid-term 📆 (3-6 months), and long-term 🗓️ (3-5 years).

## 🛠️ Project Overview

Our project uses a range of machine learning techniques to predict stock prices. We aim to build a model with higher accuracy than traditional methods by employing the following models:

- **Linear Regression** 🧮
- **Support Vector Machine (SVM)** ⚖️
- **K Nearest Neighbor (KNN)** 🤝
- **Decision Tree (DT)** 🌳
- **Random Forest (RF)** 🌲🌲
- **Artificial Neural Network (ANN)** 🧠

We discovered that no single model works best for all time horizons. Therefore, we combined these techniques and assigned weightages to each, ensuring more accurate predictions by leveraging the strengths of different models. 🛡️

## 📚 Tools and Technologies

- **IDE Software:** Jupyter Notebook 📒
- **Programming Language:** Python 🐍
- **Libraries:** Numpy, Pandas, Matplotlib, Scikit-Learn 📊
- **Website Building:** HTML, CSS, JavaScript 🌐
- **Connectivity:** Flask, Fetch API 🔧
- **Data Source:** Yahoo Finance 📉
- **Version Control System:** Git 🛡️

## 🔄 Data Flow and Methodology

Our data flow involves several key steps:

1. **Data Collection:** 📥 Download stock prices from Yahoo Finance.
2. **Data Preparation:** 🛠️ Extract key values (Close, Open, Low, High) and convert them into numpy arrays.
3. **Feature Engineering:** 🔍 Add features like Technical, Momentum, Volume, and Volatility indicators.
4. **Model Training:** 🎓 Use sklearn to train various models on historical data.
5. **Sliding Window Approach:** 🔄 For short-term predictions, we use a sliding window technique, retraining the model daily with the latest data.
6. **Visualization:** 📊 Compare actual and predicted prices using graphs and tables.
7. **Model Combination:** 🧩 Combine models with weighted averages to enhance accuracy.

## 🌟 Visualizations and Insights

Visualizations play a crucial role in our project, helping users understand the prediction accuracy and the performance of various models. 📈 These insights allow users to make better investment decisions.

## 👥 Team and Contributions

Our project team consists of enthusiastic individuals committed to leveraging technology for better financial decisions. 🤝 We continuously improve our skills and knowledge to provide a reliable and effective solution.

## 📝 Conclusion

This project not only represents a technical challenge but also a personal journey towards better understanding the stock market and mitigating investment risks. We hope this system proves to be a valuable tool for all users interested in making data-driven investment decisions. 🌐

Thank you for exploring our project! If you have any questions or feedback, please feel free to reach out. 📧
