This project consisted on a Python script to scrape text and images from various websites that talked about Mission to Mars. Then, I created a Flask web application with a rendered HTML template designed using Bootstrap to display all the data in a central location without having to gather it manually. The data scraped and displayed was stored in a non-relational Mongo database. Additionally, I was able to connect the scraping script so that each time a button was clicked, the scraping occured once again, the database got updated, and new data was displayed. This button only works under the condition that these webpages don't change their HTML components I used for scraping. And lastly, by using Bootstrap's grid system I was able to create a responsive web app that could accomodate to any device people view it from.# web-scraping-challenge.


The scrape included a news_title with its brief explanation (news_paragraph), a featured_image, a table HTML component stored in facts, and four picture thumbnails, with their titles, of the different Mars' hemispheres stored in hemispheres.

In addition, the database will be updated and each time new data is scraped it will be saved with a "last_modified" date to know when was the last time, as you can see in the bottom of the query results. In this case, it was on September 10th of 2022.
 
