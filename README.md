# mobile-app-analysis
The project aims to develop a comprehensive **data pipeline** for the **analysis of mobile app data**, with the goal of extracting **valuable insights** and trends that can inform strategic decisions. This pipeline will begin with the collection of raw data from various sources, including app usage statistics, user feedback, and performance metrics. The collected **data** will be **cleansed** and **transformed** to ensure accuracy and consistency, enabling effective analysis. The culmination of this process is a comprehensive **report** that highlights the findings and insights derived from the **data analysis**.

**Flow of work**:
1. Identification of the [dataset](https://github.com/aliannejadi/LSApp).
2. [Dataset preparation](https://github.com/pietro-fantini/mobile-app-analysis/blob/main/mobile_app_analysis.ipynb). Use **Python Google Cloud API** to fetch the data from the cloud storage to clean them and add new relevant metrics.
3. Utilize **generative AI** to create new data points such as user demographics, categorize apps and user feedbacks.
4. Use **Python Google Cloud API** to upload the prepared dataset.
5. Write **SQL queries** to explore the dataset.
6. Connect **Google Looker Studio** to **Google Big Query** and create the [report](https://lookerstudio.google.com/reporting/1579cf20-2656-42a2-809d-5831aaec6f5d).

**Technologies used**: Python, SQL, Google Big Query, Google Cloud Storage, Google Looker Studio, Generative AI.
