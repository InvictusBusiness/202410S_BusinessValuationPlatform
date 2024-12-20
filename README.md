# A Market Value Prediction System
This is a company valuation system that our team developed.

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/s4_-kWb1B5I/0.jpg)](https://www.youtube.com/watch?v=s4_-kWb1B5I)
https://www.youtube.com/watch?v=
(https://www.youtube.com/watch?v=-pYu0-rnoCg)

![Pasted image 20241218135425.png](images/Pasted%20image%2020241218135425.png)
### Project Statement and Objective

Our project addresses the limitations of traditional business valuation methods. For public companies, challenges include market volatility, biases in analyst predictions, and assumptions that fail to reflect market sentiment. For private companies, the lack of comparable data and reliable metrics complicates valuations.

To tackle these problems, our AI-based Python program offers a **dynamic and convenient valuation solution**. The key objectives include:

- Providing **AI-enabled forecasting** for enhanced accuracy.
- Reducing reliance on assumptions to combat bias.
- Integrating **financial ratios and news sentiment** for holistic valuation.
- Simplifying financial data visualization for better decision-making.
- Supporting private company valuations with custom data inputs.

---
![Pasted image 20241218135440.png](images/Pasted%20image%2020241218135440.png)
![Pasted image 20241218135534.png](images/Pasted%20image%2020241218135534.png)
### Program Overview and Responsibilities

Our program is built on **three pillars of functionality**:

1. **Company Financial Summary and Valuation**  
    It includes company-specific information such as balance sheets, income statements, and discounted cash flow (DCF) valuation.
    
2. **S&P 500 Company Analysis and Valuation**  
    A dashboard is generated featuring historical data, value predictions, recommendations, and sustainability scores.
    
3. **Sector Analysis**  
    The program provides insights into sectors, including market cap heatmaps, stock trends, and company recommendations.
    

![Pasted image 20241218135551.png](images/Pasted%20image%2020241218135551.png)The workflow involves user interaction at each stage:

- Users input company data or choose tickers/sectors.
- The program dynamically calculates financial metrics and forecasts.
- Insights are visualized in user-friendly dashboards.

---

### Workflow and Contributions

Our team followed a structured workflow:

1. **Conceptualization**: Selecting datasets and defining the program’s features.
2. **Data Collection**: Writing functions for gathering company and sector information using `yfinance`.
3. **Model Development**: Building prediction models using DCF and sentiment analysis.
4. **Dashboard Design**: Visualizing financial data and formatting outputs for better insights.

---

### Enterprise Value Prediction Model

For **private companies**, we leverage **K-Means clustering** and AI-enhanced DCF models:

- K-Means groups firms based on financial metrics like market cap, revenue, and PE ratio.
- This approach reduces subjectivity and adapts to evolving market conditions.

**Target Customers** include:

- Business owners, angel investors, venture capitalists, and private equity firms.

For **public companies**, we combine DCF and **Lasso Regression** models:

- Sentiment scores are used to predict growth rates.
- Optimistic and pessimistic scenarios are forecasted for stock price predictions.

---
![Pasted image 20241218135708.png](images/Pasted%20image%2020241218135708.png)
![Pasted image 20241218135658.png](images/Pasted%20image%2020241218135658.png)
### Sentiment Analysis and Revenue Prediction

To incorporate real-time market sentiment, the program:

1. Gathers financial news from Hugging Face datasets and Yahoo Finance.
2. Utilizes sentiment classifiers, such as **VADER**, to evaluate news sentiment.
3. Builds a **linear regression model** to predict revenue growth based on sentiment and financial metrics.

With this approach:

- Lasso regression adjusts stock price predictions based on sentiment scores.
- Confidence intervals provide a range for revenue growth forecasts.
![Pasted image 20241218135726.png](images/Pasted%20image%2020241218135726.png)
---

### Features and Innovations

The program's core innovations include:

1. AI-enhanced models that adjust dynamically to market sentiment.
2. Real-time data integration to reduce biases in valuations.
3. Dashboards that simplify financial information for better decision-making.
4. Flexibility to support both private and public company valuations.

In conclusion, our project bridges the gap between traditional valuation limitations and real-world market needs by leveraging AI, sentiment analysis, and financial modeling.
