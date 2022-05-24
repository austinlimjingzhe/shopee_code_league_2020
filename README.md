# Shopee Code League 2020

<h1>EVENT BACKGROUND</h1>

Shopee Code League is a 2-month online coding challenge consisting of a series of competitions, online algorithm questions and online training workshops open to all 
undergraduate students and professionals across the region (Singapore, China, Indonesia, Malaysia, Philippines, Taiwan, Thailand and Vietnam).

Shopee Code League 2020 operated online entirely from 8 June to 1 August 2020. There were 8 competitions ranging from data analytics, to data science and algorithms, all
of which have been specially designed by Shopee tech teams. Participants must analyse the dataset, draw insightful conclusions and solve the problems in a specified 
amount of time via an online platform.

Special thanks to my team, Team Waterloo, for the opportunity to join the competition.

<h1>Marketing Analysis</h1>
<h2>Background and Task</h2>
The aim of this project is to build a model that can predict whether a user opens the emails sent by Shopee.<br><br>

Sending emails is one of the marketing channels Shopee uses to reach out to users. Being able to predict whether a user opens an email allows Shopee to forecast and evaluate the performance of future marketing campaigns before launch. This is because when a user opens an email, the probability of the user knowing the campaign increases and this in turn increases the probability of the user making a checkout during the campaign period. Therefore, with the predicted open rates, Shopee can better develop, strategize and implement future marketing campaigns.<br>

Participants are provided with data related to marketing emails (Electronic Direct Mail) that were sent to Shopee users over a certain period. It contains information about:

1. User-specific information
2. Email nature
3. Users’ engagement on the platform
4. User’s reaction to the email, including whether users opened the email

Based on the data provided, participants must predict whether each user will open an email sent to him/her.

<h2>Methodology</h2>
An artificial neural network was used to make predictions onto the test set. More details can be found in the Jupyter Notebook files.

<h1>Sentiment Analysis</h1>
<h2>Background and Task</h2>
Shopee always strive to ensure the customer’s highest satisfaction. Whatever product is sold on Shopee, they ensure the best user experience starting from product searching to product delivery, including product packaging, and product quality. Once a product is delivered, they always encourage their customer to rate the product and write their overall experience on the product landing page.<br><br>

The rating and comments provided for a product by buyers are most important to Shoppee. These product reviews help them to understand their customers needs and quickly adapt their services to provide a much better experience for their customers for the next order. The user's comments for a product ranges from aspects including delivery services, product packaging, product quality, product specifications, payment method, etc. Therefore it is important to build an accurate system to understand these reviews which has a great impact on overall Shopee’s user experience. This system is termed: "Shopee Product Review Sentiment Analyser".<br>

In this competition, a multiple product review sentiment classification model needs to be built. There are ~150k product reviews from different categories, including electronics, furniture, home & living products like air-conditioner and fashion products like T-shirts, rings, etc. For data security purposes, the review ids will be desensitized.

<h2>Methodology</h2>
Developed in Google Colab, a BERT model was used to do multiclass classification of sentiments of reviews. More details can be found in the Jupyter Notebook files.
