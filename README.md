# TFM Kschool Javi Carmona
 
 [![](https://img.shields.io/badge/Contact-Javier_Carmona-blueviolet)](https://www.linkedin.com/in/javiercarmonag/ "![](https://img.shields.io/badge/Contact-Javier_Carmona-blueviolet)")
 

 ![](https://img.shields.io/badge/Python-v3.7-9cf) 

![](https://img.shields.io/badge/View-KSCHOOL_TFM-orange) 


#### [The submision ](http://bit.ly/TFM_JaviCarmona)


While it´s very impressive that today's technology allows us to gather incredible amounts of data, the reality is that much of this data is currently collected before anyone answers: “What do we want to do with this data?" The result: WPP has a lot of data and people don´t know about it.

I have worked in a dashboard where people, who are not used to work with data, understand all the data that WPP has available.

The objective is to create an easy and useful dashboard, but also a dashboard that is always updated, now with 276 datasets and in one year from now who knows, hopefully with thousands of datasets. The dashboard must be updated easily and fast to make all the data accessible to all the WPP Group in a daily basis.

### Topics

- **Insigths:** Clear insights are a must. To understand in an easy way what data WPP has and if it is useful for anyone who arrives at our dashboard, I try to look for insights that are not readily visible and answer questions like when or where.
- **Visualization:** I decided to use DataStudio because it is very easy to connect to multiple platforms and it fits perfectly with the dashboard I want to develop. 
- **Comprehensiveness:** Interesting insights but easy to understand with clear and direct charts that are updated when a new dataset is uploaded.
- **Code:** All the code has been developed to be usable and to let us have the dashboard always updated. I have used the dataset of url-collection-topic as a starting point. From there, I use the urls to extract all the metadata from the dataset and work with it. After you add a new dataset to this dataset, you only have to execute the code to have the dashboard fully updated. 

### What have I done? 
The main goal is to give our agencies the opportunity to use WPP data to improve their performance with clients.
I connect with the API and the dataset with all the URLs to export all the metadata and I start to work with it creating 5 final dataframes.
1. **Countries.** Dataset titles and all the countries inside the summary text.
2. **Dates.** Dataset titles and all the dates inside the summary text. When I detect a range (for example from 2000 to 2020) I include all the dates inside the range.
3. **Tags.** Dataset titles and all the tags of each one. 
4. **Full data.** Dataset with all the info from the metadata. From title to collection, privacy, description... 
5. **Summary.** Summarize what I have, how many datasets? How many countries? When have I got data from? 


_In the next figure I can see the architecture that has been used to develop our solution. Everything is in the cloud._

![](http://digitalworldtrends.com/Data_Studio/Images/008.jpg)

### Visualization 

What are you going to find on the Dahsboard?

- **Updated date.** Every time the code runs the date is updated.  

- **Quick insights,** because it is very interesting to understand how big is the data from WPP. 

![](http://digitalworldtrends.com/Data_Studio/Images/001.jpg)
- **Charts**, the objective of these charts is to show very fast all the categories and what data is available from WPP.
World map with what countries are included in our datasets.
Sunburst to review the collections and topics.
Timeline with the years about I have data.
Word Cloud with a quick overview of the tags of all the datasets.

![](http://digitalworldtrends.com/Data_Studio/Images/003.jpg)

- **Data table**, after reviewing the different options that you can filter the data, it is time to go deep in, now with the data table the user can filter all the datasets from collection, topic, country and year and access to the dataset. 

![](http://digitalworldtrends.com/Data_Studio/Images/004.jpg)









