# Youtube-Title-Contest

Created a quick webscraper to pull the top 200 most viewed videos from the search results of "iphone battery repair" to help my friend create a clickbait title for his new video. Definitely isn't polished or clean, but it's a good prototype. 

The output is a wordcloud with the most commonly used words in the title: 

![image](https://user-images.githubusercontent.com/20735594/130367850-f086b7b5-c135-42b3-8a9b-e42c7ac01504.png)

Since I was on a deadline, the data isn't 100% clean, nor is the wordcloud very clear, but that's something to work on eventually. 

One of the files is uses the YoutubeAPI to pull results, but is unfinished due to Youtube's limits on the number of results that can be pulled at once. I might go back to it when I have the time to fix it to use the pagination to pull results. 

The other two Jupyter notebooks contain the code for the wordcloud, one of them using a dataset I took from RapidAPI (which had some issues pulling the data) and the other contains the webscraper I built from scratch. 
