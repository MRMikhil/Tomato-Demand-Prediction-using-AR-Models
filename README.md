**Aim:**
The primary aim of this study was to evaluate the effectiveness of autoregressive models, specifically AutoRegressive Integrated Moving Average (ARIMA) and Seasonal AutoRegressive Integrated Moving Average (SARIMA), in predicting the prices of highly volatile commodities such as tomatoes. Given the unpredictable nature of commodity prices, which are influenced by a variety of external factors, the study sought to determine whether these models could provide accurate and reliable predictions for such commodities.

**Introduction:**
Commodity prices, especially those of agricultural products like tomatoes, are subject to frequent and often unpredictable fluctuations. These fluctuations are driven by factors such as seasonal variations, weather conditions, supply chain disruptions, and shifts in consumer demand. Traditional predicting models, including autoregressive approaches like AutoRegressive Integrated Moving Average (ARIMA) and Seasonal AutoRegressive Integrated Moving Average (SARIMA), are commonly used to predict future prices based on historical data. However, the effectiveness of these models in the context of highly volatile commodities remains questionable, and this study aims to explore their limitations and potential inaccuracies.

**Analysis & Findings:**
In this study, historical price data for tomatoes was analyzed using autoregressive models. The AutoRegressive Integrated Moving Average (ARIMA) model, which is designed to capture the underlying trend and seasonality in the data, was first applied. However, the lowest Mean Absolute Percentage Error (MAPE) achieved by this model was 86% (Fig 1.1), indicating a substantial gap between the predicted and actual prices. This high error rate suggests that the AutoRegressive Integrated Moving Average (ARIMA) model struggled to accurately predict the volatile price movements of tomatoes.


Fig 1.1 ARIMA Predictions
![image](https://github.com/user-attachments/assets/43001f70-130b-4843-92e5-6a162e89d2e5)


Fig 1.2 SARIMA Predictions
![image](https://github.com/user-attachments/assets/4071e6e2-62aa-423b-a628-b7d90c76ae0d)

 
Next, the Seasonal AutoRegressive Integrated Moving Average (SARIMA) model was applied, which attempts to account for seasonal patterns that may influence price changes. While this model performed slightly better, it still yielded a significant error, with the lowest Mean Absolute Percentage Error being 36% (Fig 1.2). Although this is an improvement over the AutoRegressive Integrated Moving Average (ARIMA) model, the error rate remains too high for practical predicting purposes, particularly in the context of commodities like tomatoes, where sudden and sharp price changes are common.

**Conclusion:**
The findings of this study indicate that autoregressive models, including both AutoRegressive Integrated Moving Average (ARIMA) and Seasonal AutoRegressive Integrated Moving Average (SARIMA), are not suitable for predicting the prices of highly volatile commodities such as tomatoes. Despite the inclusion of seasonal adjustments in the Seasonal AutoRegressive Integrated Moving Average model (SARIMA), the lowest Mean Absolute Percentage Error (MAPE) of 36% is still too high, highlighting the limitations of these models in accurately capturing the complexity and unpredictability of commodity prices.

The aim of the study was to assess the usefulness of these autoregressive models in predicting commodity prices, and the results conclusively show that they fall short in this context. These findings suggest that alternative approaches, which incorporate a broader range of influencing factors beyond historical price data, may be necessary for more accurate and reliable predicting of highly volatile commodities.

**Future Scope:**
Given the limitations identified in the use of autoregressive models for predicting volatile commodity prices like those of tomatoes, future research should explore more advanced predicting techniques that can better handle the complexity and unpredictability of such markets. Machine learning models, such as neural networks and ensemble methods, could be investigated for their ability to capture non-linear patterns and external factors influencing commodity prices. Additionally, hybrid models that combine traditional statistical approaches with modern machine learning techniques could offer improved accuracy by leveraging the strengths of both methodologies. Another promising direction would be the incorporation of real-time data, such as weather conditions, market sentiment, and supply chain disruptions, to enhance the responsiveness and precision of predicting models. Future studies could also explore the potential of integrating macroeconomic indicators and global market trends to develop more robust and comprehensive predicting tools for agricultural commodities
