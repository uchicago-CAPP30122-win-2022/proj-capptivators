Capptivators - Crime Data & Twitter Analysis by Major US City, 2005-2021

The app scrapes twitter using twint, performs cluster and sentiment analysis, merges the findings with fbi data on crimes by major US city, and creates a dash dashboard. The app is set up to run the dashboard on data that is already prepared and aggregated, but the twitter scraping and sentiment code is in the twitter folder.  



To run the app: 

(1) Enter the virtual environment while you are in the proj-capptivators folder by running: source install.sh 
(2) Enter into the crime_sentiment folder 
(3) From the crime_sentiment folder, run: python3 -m crime_sentiment
(4) Dashboard will display on http://127.0.0.1.8051/



Structure of the app: 

crime_sentiment 
-__init__.py /n
-__main__.py
-__pycache__ 
-app.py
-dashboard
    -crime.py
-data
    -fbi
        -Crime_2000_2018.zip
    -twitter
        -aggregated_results
        -sentiment_disaggregated_results
        -tweets_downloads
    -fbi_twitter_merge
        -crime_data.csv
-sentiment
    -twitter_data.py
    -twitter_df_pro.py
    -aggregation.py
-project_feedback
    -proj_d1.md 
    -proj-d2-feedback.md
    -proj_d2.pdf
install.sh
README.md - this file
requirements.txt


