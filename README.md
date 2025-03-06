# DA Analytics: Exploring Data and Building Machine Learning Models for Used Car Price Estimation in Saudi Arabia

**1. Introduction**

Our Team Company analyzing used car sales data from Syarah.com, a marketplace platform in Saudi Arabia. In a marketplace model, businesses distribute product from seller to individual consumers, making platforms like Syarah.com a key player in the online used car marketplace.

Syarah.com has established itself as a leading platform for buying and selling used cars in Saudi Arabia. In 2021, the company successfully sold over 20,000 used cars, demonstrating its strong presence and influence in the market.

---

**2. Why Need Analysis ??**

- One of the biggest challenges for sellers is setting the right price for their cars. Pricing too high can deter buyers, while pricing too low can result in losses for the seller.
- To address this challenge, Syarah.com introduces a **Machine Learning-based price prediction feature** that helps sellers determine the optimal price based on real-time market data. This feature analyzes various factors, including brand, model, production year, mileage, vehicle condition, and market trends.
---
**3. Who are the affected Side ?**
- For Sellers: Avoid underpricing or overpricing, making it easier to attract buyers while ensuring profitability.
- For Businesses: Gain more profits from the subscription of machine learning on Syarah.com
---
**4. Goals**

This project aims to develop a **Machine Learning model** that can **accurately predict the price of used cars**. By leveraging historical sales data, this model will help sellers **determine the optimal price**, enhancing market competitiveness and maximizing profits.  

 **Why Is This Important?**  

 **- More Accurate Pricing**  
- With this model, car prices will better reflect current market conditions, preventing them from being too high (which can discourage buyers) or too low (which can result in seller losses).  

 **- Increased Efficiency and Reduced Costs**  
- Pricing, which was previously determined manually, can now be automated, saving time and resources for sellers.  

 **- Boosting Syarah.com’s Revenue Through Premium Subscription**  
- This price prediction feature will be **exclusively available to premium account users**, adding value to those who subscribe.  
- With a subscription, sellers gain access to data-driven price analytics, helping them sell cars faster at the best price.  

 **- Maintaining Business Competitiveness**  
- The used car market is constantly evolving. With a solid prediction model, pricing can remain **competitive and dynamic**, making it easier to attract customers and increase transactions on Syarah.com.
---
**5. What Effect is Available When models are Implemented**

- For Syarah.com, this feature not only enhances the platform’s value for sellers but also creates a new monetization opportunity through **premium account subscriptions**, increasing overall profitability. With this AI-powered solution, Syarah.com solidifies its position as an innovative and data-driven automotive marketplace.

- By subscribing, sellers gain benefits such as:  

  - **Accurate Price Estimation** – Sell cars at the best price based on the latest market data.  

  - **Faster Sales** – Competitive pricing increases the chances of selling cars more quickly.  

  - **Competitive Advantage** – Premium sellers gain access to exclusive analytics not available to free users.  

   **Syarah.com Subscription Pricing Recommendations**  

     **- Basic Plan (SAR 49/month)**  
    - 3 price predictions per month  
    - Access to price analytics dashboard & market trends  
    - Optimal price recommendations  
    
     **- Dealer Plan (SAR 299/month)**  
    - 50 price predictions per month  
    - Access to price analytics dashboard & market trends  
    - Optimal price recommendations  
    - Priority customer support  
    - Exclusive discounts on listing promotions on Syarah.com  
    
     **- Additional Prediction Quota (SAR 199)**  
    - Add 50 predictions  
    
     **Flexible Pricing Option**  
    As an alternative, a "Pay Per Use" option can be offered, such as **SAR 20 per price prediction** for those who do not want a monthly subscription.
---
**6. When the model is used ??**

To optimize this process, a Machine Learning (ML) model will be implemented before seller input price stage. The ML model will predict the optimal price for the car based on various factors, such as:

  - Car brand, model, and year
  - Mileage and engine condition
  - Gear type and additional features

**How ML Helps in Pricing Used Cars**
  
  - When a subscribed seller inputs their car details, the ML model will suggest a price range.
  - The seller can then choose to accept the suggested price or adjust it accordingly.
  - Reduces overpricing or underpricing risks, making the sales process more efficient.
  - Helps the platform gains profit, increasing trust and engagement.
  
Key Point
  
  - ML Model Type: Regression-based model for price prediction
  - Main Implementation: When the subscribed seller fills in the car details
  - Objective: Provide a competitive, data-driven price recommendation
---
**7. Analysis Process Flow**

To solve the pricing challenge in Saudi Arabia’s used car market, we’re going to build a Machine Learning (ML) model that predicts car prices based on historical data. Since we’re working with continuous price values, this falls under Regression ML.

**- Understanding the Data**
**- Preparing the Data for ML**
**- Choosing & Training the Model**
**- Making the Model stabilize**

As for the process of making a model by considering business problems, the evaluation metric are

---
**8. Metric Evaluation**

  - MAE (Primary Metric): It is a good choice because its unit follows the original data unit. It is useful when the data contains outliers, as it is not affected by them. This will be the main focus for this Machine Learning model since the data contains outliers.
  - MAPE (Secondary Metric): Useful for understanding the percentage of error.
  - R-Square: Used to evaluate a model's performance. The closer it is to 1, the better the model fits the data. However, this does not necessarily mean the predictions will be accurate.
  - RMSE: Places more weight on errors in outlier data, making it suitable for focusing on reducing prediction errors.

**Why MAE first?**

- In this case, we put MAE on the top priority because MAE measures the average absolute difference between predicted and actual prices. For example, if a model's MAE is SAR 1,500, it means that, on average, the predicted car prices have an error of about SAR 1,500 from the actual market prices. This metric is easier for users to understand compared to others like MSE or RMSE, which are based on squared differences.

- For Syarah.com, this means the model can remain accurate for the majority of cars without being affected by a few extreme-priced vehicles, resulting in more realistic predictions for premium customers.

The smaller the MAE and MAPE values, the more accurate the model will be in predicting car prices based on the limitations of the features used.

---
**! You want to see More ???**

This Github Provide
  - To be able to view the analysis file you can access ipynb available on this github, Analysis File in the form of a file IPYNB
  - Dashboard based on Analysis you could Access by [Click Here](https://public.tableau.com/app/profile/ramadhyan.de.surya/viz/UsedCarDashboard_17410944222040/Dashboard2?publish=yes).
  - Prototype Model Application Deployed in the form of a file Folder Strimlit or see **Note** below
  

** Note : For run the Prototype Model using Strimlit you can run Manually after downloading the Folder by type this in RUN Terminal (Run Strimlit "FolderPath\Homepage.py"), or you can access our deployed Model by <a href="https://finprogammajcds0508strimlit-npqm3st5yq6zpttzyebnfq.streamlit.app/" target="_blank">Click Here</a>


