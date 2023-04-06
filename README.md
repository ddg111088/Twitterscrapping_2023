# Twitterscrapping_2023

#Twitter-scraping-with-snscrape-and-streamlit

APPLICATION LINK:  
Interative GUI using streamlit for twitter scraping
REQUIRED SKILLS:
1.	Python scripting
2.	MongoDB
3.	Streamlit
4.	Snscrape

OVERVIEW:
The sidebar of the GUI I made with streamlit has the following capabilities.
1.	Can enter any keyword or Hashtag to be searched,
2.	select the starting date
3.	select the ending date
4.	Number of tweets needs to be scrapped.

After scraping is done, it has the following options
1.	Download data as CSV
2.	Download data as JSON
3.	Upload data to DATABASE
4.  Display All the Tweets scraped
5.	Apply a filter based on the column
6.	All the Uploaded Collections in Database are Displayed in the left side

WORKING:

Step1: Initially, I used the streamlit sidebar to gather the user's Keyword, Start date, End date, and Number of tweets. 

Step 2: TwitterSearchScraper and TwitterHashtagScraper are given the aforementioned information. The complete scraped data is placed in a dataframe, which is then available for download in CSV or JSON format.I added an additional choice. If unnecessary, streamlit_extras can be omitted.

Step3: Using pymongo, the database link is made. If a user chooses to upload data, a new collection is made and the data is uploaded there.

Step4: created a thorough overview of the user input that was displayed on its main page.

HOW TO RUN TWITTER SCRAPER IN YOUR MACHINE: open cmd:
1.	C:\Users\mypc> pip install streamlit
2.	C:\Users\mypc> pip install streamlit.extras
3.	C:\Users\mypc> pip install snscrape
4.	C:\Users\mypc> pip install pandas
5.	C:\Users\mypc> pip install pymongo
6.	Using the Python IDE, write your code and run it.
7.	C:\Users\mypc>streamlit run my_twitter_scraper.py
8.	You can now view your Streamlit app in your browser.
9.  Local URL: http://localhost:8501
10.	Network URL: http://192.168.107.230:8501

After clicking on the above url you can see the app in your browser
TWITTER SCRAPER STREAMLIT APP WORKING DEMO VIDEO
