# DTSA-5800


Network Analysis for Marketing Analytics Final Project

In this repository you will find the Colaboratory Notebook related to my final project.

Problem Description

For this project, you're going to do an analysis of how consumers talk about three competing brands: Nike, Adidas, and Lululemon. 

Do a network analysis of the tweets that are created that mention those brands. As you know, Twitter is an interesting place where people, bots and organizations all join the conversation. Your goal for this project is to better understand the chatter around each brand, what makes each brand unique, and what makes each brand different. We also will use network analysis to identify users that are most central to our brand and ones that are hyper interested in our product category in general, here athletic wear.

About the data...

We used the Twitter API, specifically the Search Endpoint, to retrieve Tweets that mention the three brands. We retrieved data for the last 93 days. All in all, it’s about ~150k tweets. These tweets are “at Mentions” (@nike, @lululemon, @adidas). These tweets were sent from the US and are in English. Presumably, these mentions contain all kinds of conversations:

Consumer / customer mentions, alerting Nike to a message, or tagging them in their experience

Other brands who cross promote and their corporate messaging

Affiliated companies, such as retail stores and their corporate messaging

Probably random spam bots mentioning the brands

God knows what else that lives on the far reaches of Twitter

The data is saved here:

http://128.138.93.164/nikelululemonadidas_tweets.jsonl.gz

It is in .jsonl format. We’ll go over how to parse it in our coding lectures.
