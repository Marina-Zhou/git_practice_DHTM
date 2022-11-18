# **Project Title**<br />
Create a depression tweets text dataset<br />

## **Description**<br />
Depression is one of the most common psychological disorders in modern society, which has a great negative impact on people's life and work. But after active treatment of depression patients, between 80% and 90% percent of them eventually respond well to treatment.<br />

By collecting a dataset of depressive tweets, researchers can better identify users with potential depression as early as possible, join hands with social media platforms and relevant government departments to provide appropriate support and help them recover.<br />

## **RQ & hypothesis**<br />
Whether it is possible to accurately scrape text containing depressed words from the Twitter and then create a database containing depressed tweets with an accuracy rate of 80% or more.<br />

## **How to address RQ**<br />
1.To create a scraper to identify potential depression tweets, for example, tweets with hashtag #depressed, #depression<br />
2.To process data:<br />
a.Delete duplicate tweets<br />
b.Delete tweets including positive, medical or education hashtags.<br />
c.Delete tweets including over 3 hashtags, “@” and website.<br />
d.Remove tweets with less than 25 characters, or 5 words.<br />
e.Remove all hashtags from the tweets.<br />
f.Make sentiment analysis to remove the positive tweets.<br />

## **Results test**<br />
Dataset will be stored in a CSV file and needs to be made a sampling inspection to test whether there are positive tweets inside to calculate an accuracy rate.<br />

## **Tools**<br />
Python/command line tool twarc, pandas, VADER<br />

## **Resources**<br />
[Anne Bonner's Medium article You Are What You Tweet.](https://towardsdatascience.com/you-are-what-you-tweet-7e23fb84f4ed)<br />

[Depression Detection Using Twitter Data - Group project for Udacity Private & Secure AI Project Showcase](https://github.com/swcwang/depression-detection)<br />

