<h1>SVOD Online Brand Sentiment Market Research</h1>
<h2>The objective of this project is to perform sentiment analysis on news articles related to three streaming companies (Netflix, HBO, and Disney) and identify patterns in the sentiment scores.</h2>
1. The problem we are solving is understanding the sentiment of news articles related to these streaming companies. By analyzing the sentiment scores of news articles, we can gain insights into how the media perceives these companies and their products.
<br>
<br>
2. We are solving this problem by collecting news articles related to Netflix, HBO, and Disney, and performing sentiment analysis on the articles using natural language processing techniques. We are also analyzing the data using SQL to identify patterns in the sentiment scores.
<h2>Marketing Data Analyst</h2>
1. Deloitte is a professional services firm that offers various services, including audit, consulting, financial advisory, risk management, and tax services. The Marketing Data Analyst at Deloitte is responsible for analyzing and interpreting marketing data to provide insights that drive business decisions. The position requires strong analytical skills, proficiency in statistical analysis software such R, and the ability to collaborate with cross-functional teams to support the development and execution of marketing strategies.
<br>
<br>
2. This project could simulate a market research component to a larger research effort into the SVOD industry, or for a company within this industry
<h2>Data</h2>
1. The data for this project was collected using the NewsAPI. The API was queried to retrieve news articles related to Netflix, HBO, and Disney.
<br>
<br>
2. The data includes news articles from a variety of sources, and covers the time period from January 1, 2021 to March 31, 2021. Each article includes the article title, description, and source, as well as a sentiment score generated using natural language processing techniques.
<h2>Notebooks</h2>
Data Collection Notebook; pulled 300 articles from newsapi about Netflix, HBO, and Disney
https://github.com/jlee8639/ISBA-4715_2/blob/main/data_collection_Jay_Lee(2).ipynb
<br>
Data Analysis Notebook; calculated sentiment scores for all articles using python package
https://github.com/jlee8639/ISBA-4715_2/blob/main/data_analysis_Jay_Lee(1).ipynb
<br>
SQL Analysis Notebook; conducted 5 exploratory queries and 3 business intelligence queries
https://github.com/jlee8639/ISBA-4715_2/blob/main/sql_analysis_Jay_Lee(1).ipynb
<h2>Future Improvements </h2>
I would look into a better sentiment analysis tool because some of the article descriptions were not negative, but would be rated negative due to poor recognition by the tool. Another thing to look into is getting more data overtime to see trends.
