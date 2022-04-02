<p align="center">
  <img src="datasciencebannernew.jpg" >
</p>

# Hello everyone! It's a pleasure to have you here.

Here you will find my professional experiences, skills, tools and projects involving Data Science.

As the projects below demonstrate, I am able to implement a complete Data Science project (“end-to-end”), from obtaining business requirements to publishing it in the cloud, including creating tools to access the Machine Learning Models for non-tech people.

## Skills:
* **Programming Languages:** Python.
* **Databases:** SQL (SQLite, PostgreSQL).
* **Data visualization:** Python libraries (matplotlib, seaborn, folio), Streamlit, Telegram bots.
* **Descriptive Statistics:** Central Tendency, Dispersion, kurtosis, density.
* **ML Algorithms:** Supervised Learning (Regression, Classification and Learn to Rank). Linear Regression, Logistic Regression, Lasso Regression, Random Forest, XGBoost, ExtraTrees, K-Nearest-Neighbours (KNN).
* **Data Balancing:** Attribute Selection and Dimensionality Reduction techniques.
* **ML Performance Metrics:** RMSE, MAE, MAPE, Confusion Matrix, Precision, Recall, Accumulative, ROC and AUC curves.
* **ML Libraries (Python):** sklearn, scipy, pycaret.
* **Version Control:** Git (code versioning), and DVC (data versioning).
* **APIs:** Flask, Streamlit, Amazon API Gateway.
* **MLOps:** AWS tools (S3, EC2, Lambda), Heroku cloud, DVC, MLflow.   


## Data Science Projects:

### Sales Forecast
* **Business Problem:** The CFO of a drugstore chain wanted a sales forecast for each individual store for the next 06 weeks.
* **Solution Strategy:** Following the steps of the CRISP-DM framework, first I performed data analysis to extract insights and validate business hypotheses. Then, I performed the selection and validation of Machine Learning algorithms, choosing XGBoost for the balance between computational performance and accuracy. Finally, I deployed the application in the cloud (Heroku). Access to forecasts is made possible through a Telegram bot created by me.
* **Business Result:** The choosen model presented an absolute mean percentage error (MAPE) of 15%. The expected revenue was in the range of R$ 275.15 - 277.46 (millions R$).Information about the drugstore sales forecasting was shown on a [Telegram Bot](https://t.me/rossmansales_bot).
* **Project:** [**Sales Forecast Drugstores**](https://github.com/joaomj/rossman_main).

---
### Marketing Budget Optimization

* **Business Problem:** An insurance company wanted to sell another insurance policy (vehicle insurance) to its clients. However, due to the limited amount of its marketing budget and the size of its customer base, the company wanted to know which customers should be given priority in receiving a cross-sell proposal.
* **Solution:** After understanding the problem (optimizing the use of the marketing budget), the company's data science team adopted a strategy of classification: customers will be classified according to the probability of purchasing the new insurance. This probability will be provided by a Machine Learning algorithm. With the clients dataset ordered by purchase probability, the marketing team will be able to focus its efforts only on the customers that are at the top of the sorted dataset ( = greater purchase probability).
* **Business Result:** with the Machine Learning model adopted, the marketing team was able to approach 90% of interested customers by covering only 40% of the clients database. Assuming a cost per call of $10.00 and considering the total number of customers (381,109), the company achieved savings of $2,286,660 on phone calls costs (60% cost reduction).
* **Project**: [**Marketing Optimization**](https://github.com/joaomj/health_insurance_cross_sell)

---
### Exploratory Data Analysis of Real Estate Data

* **Business Problem:** The CEO of a real estate company located in King County wanted to know which properties available for sale would be a good business opportunity.
* **Solution:** The data team's approach consisted of analyzing all properties in the county available for sale and finding those priced below market price ( = median price per m2 in each zip code). We would recommend buying the property if it is below market price and in good condition. Then the property would be resold at market prices.
* **Business Result:** Thanks to this simple data analysis, the company was able to resell properties for up to 30x the purchase price.
* **Project**: [**Exploratory Data Analysis**](https://github.com/joaomj/House-Rocket-Analytics)

---

### Curiosities about me:

* **Areas of Interest:** Data Science, MLOps, Financial Analysis (stocks) and History :sunglasses: .
* Bachelor degree in Computer Science through Sao Paulo State University (UNESP).

[![Joao's GitHub stats](https://github-readme-stats.vercel.app/api?username=joaomj&show_icons=true&theme=radical)
