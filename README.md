**YOUTUBE DATAHARVESTING AND WAREHOUSING USING SQL AND STREAMLIT**




OVERVIEW:

In this project, we aim to build a robust data pipeline for collecting, storing, and visualizing YouTube data. The pipeline will involve scraping data from YouTube using the YouTube API, storing it in MongoDB for efficient data management, integrating it with SQL Server for relational analysis, and finally showcasing the insights through a Streamlit web application.





PROJECT DESCRIPTON:


DATA SCRAPING FROM YOUTUBE:

We will utilize the YouTube API to gather data from various channels, videos, comments, and other relevant metadata. This includes information such as video titles, descriptions, view counts, likes, dislikes, comments, and timestamps. The data scraping process will be designed to collect a large volume of relevant information efficiently and ethically.

DATA STORAGE IN MONGODB

Once the data is scraped, it will be stored in MongoDB, a NoSQL database known for its flexibility and scalability. MongoDB's document-oriented structure makes it ideal for storing unstructured or semi-structured data like the varied content found on YouTube. We will design schemas and collections in MongoDB to organize the scraped data effectively, allowing for easy retrieval and manipulation.

INTEGRATION WITH SQL SERVER:

To enable relational analysis and further processing of the data, we will set up integration between MongoDB and SQL Server. This will involve extracting data from MongoDB and loading it into SQL Server tables. By leveraging the strengths of both NoSQL and relational databases, we can perform complex queries, aggregations, and joins to derive valuable insights from the YouTube data.

STREAMLIT VISUALIZATION:

The final stage of the pipeline involves creating a user-friendly web application using Streamlit. We will develop interactive dashboards and visualizations that showcase the insights derived from the integrated YouTube data. Users will be able to explore trends, analyze engagement metrics, and gain actionable insights through intuitive and responsive visualizations presented in the Streamlit app.





KEY FEATURES:


Automated data scraping from YouTube using the YouTube API.
Efficient storage and management of scraped data in MongoDB.
Integration of MongoDB with SQL Server for relational analysis.
Development of interactive dashboards and visualizations in Streamlit.
User-friendly interface for exploring YouTube data insights.




REQUIRED LIBRARIES:


googleapiclient.discovery

pymongo

psycopg2

pandas 

streamlit 
