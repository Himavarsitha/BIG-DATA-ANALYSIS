# BIG-DATA-ANALYSIS

COMPANY:CODTECH IT SOLUTIONS

NAME:Anguluri Hima Varshitha

INTERN ID:CT08ILS

DOMAIN:Data Analysis

DURATION:4 weeks

MENTOR:Neela Santhosh Kumar

Description:The task I completed involved performing a comprehensive sentiment analysis on a dataset of tweets directed at various airlines. The dataset, Tweets.csv, contained information such as tweet text, sentiment (positive, neutral, negative), airline names, reasons for negative feedback, and timestamps. Using Dask for efficient data processing and Matplotlib/Seaborn for visualization, I explored the sentiment distribution, analyzed the reasons behind negative feedback, and examined trends over time. The analysis was started by importing the dataset into a Dask DataFrame to facilitate efficient handling of large-scale data. Columns were dropped, as they were redundant, and rows with missing values in critical fields such as airline_sentiment and text were dropped to ensure that the data would be of high quality. An analysis of sentiment distribution indicated that most of the tweets had a negative sentiment with 9,178 tweets followed by neutral, which was at 3,099, and positive at 2,363. This was visualized using a bar chart, highlighting the prevalence of negative feedback.
Next, I investigated the reasons behind negative sentiment, identifying Customer Service Issues as the most common cause (2,910 tweets), followed by Late Flight (1,665 tweets) and Can't Tell (1,190 tweets). A bar chart was used to visualize this distribution, providing actionable insights into areas where airlines could improve. Besides this, I organized data by the type of airline and sentiment, allowing me to view how different airlines had variation in sentiment. Based on my research, the airlines that faced more negative tweets are US Airways and United; in contrast, Virgin America received fairly balanced amounts of both sentiments, which could be visualized on a stacked bar chart so comparisons of proportion were easy between different airlines.
To further visualize the data, I created a word cloud for negative tweets, which graphically depicted the most frequently occurring words in negative feedback. This helped me figure out what common themes and issues customers complained about. In addition to that, I plotted the temporal distribution of tweets by converting the tweet_created column to datetime format and plotting the number of tweets over time. This revealed trends in tweet activity, such as spikes on specific dates, which could be correlated with real-world events or airline incidents.Finally, I calculated the proportion of sentiments for each airline and visualized it using a normalized stacked bar chart. This provided a clear view of how sentiment was distributed proportionally across airlines, offering a more nuanced understanding of customer satisfaction.

Applications and Uses
This sentiment analysis task has numerous practical applications in the aviation industry and beyond. For airlines, the insights gained can help improve customer service, address common complaints, and enhance overall customer satisfaction. By identifying the most frequent reasons for negative feedback, airlines can prioritize areas for improvement, such as reducing flight delays, improving customer service, or addressing baggage issues. The sentiment distribution by airline can also serve as a benchmark for performance evaluation, enabling airlines to compare their performance with competitors.
For data scientists and analysts, this task demonstrates the use of tools like Dask for handling large datasets efficiently and libraries like Matplotlib and Seaborn for creating insightful visualizations. Other applications of the workflow include analyzing reviews for e-commerce platforms, feedback from hotels, or product reviews. The methods applied, like sentiment analysis, word cloud generation, and time series analysis, are very much applicable in domains such as marketing, customer relationship management, and social media monitoring.
In academic research, this analysis can serve as a case study for teaching data preprocessing, visualization, and sentiment analysis techniques. It also highlights the importance of data-driven decision-making in improving business outcomes. Overall, this task showcases the power of data analysis in uncovering actionable insights and driving meaningful improvements in various industries.

outputs:
![Image](https://github.com/user-attachments/assets/bbd481a9-13dc-41be-90ec-d0947fbc309d)
![Image](https://github.com/user-attachments/assets/47b51b93-22ff-4995-a6e3-c748848ac15a)
![Image](https://github.com/user-attachments/assets/93e76664-f87d-43d5-8386-cdc69a4f945e)
![Image](https://github.com/user-attachments/assets/40f8e379-18df-4268-b559-04e535c491cb)
![Image](https://github.com/user-attachments/assets/21ad3243-8671-43dd-9ffa-37eeb125b7b8)
![Image](https://github.com/user-attachments/assets/d8f6535c-19e2-4cde-b020-6f40822b12e1)
