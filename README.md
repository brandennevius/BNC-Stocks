# Contents
[BNC Stocks](#bnc-stocks) \
[Goals](#goals) \
[Overview](#overview) \
[Software Development](#software-development) \
[Tools](#tools) \
[To-Do](#to-do)


# [BNC Stocks](https://bncstocks.com/)
BNC Stocks was created by a friend and I to share our in-depth analysis of our stock trades with the internet. The beginning of last year I becam fascinated with the stock market and its potential to change my life. A dream of mine is to secure financial freedom, I believe this could be a great opportunity to pursue that. So I took it on as a learning opportunity and dug into some books, learning as much as I could. My friend(cam) is very knowledgeable on the topic which made him a great partner for this project. We combined our expertise's and taught each other as much as we could. And thus, BNC Stocks was born. 

# Goals
* Create a passionate like-minded community with which we can share our ideas with our users. Having a tight knit community will be the difference that will help all of us become successful traders
* Be the go-to stock analysis website on the internet
* Gain web development experience
* Gain writing/blogging experience

# Overview
The website is built around a few major ideas. The first being posting our trades with in-depth analysis. For each one, we walk the reader through why we are interested, what exactly we are doing(price, exit strategy, goals, etc.) And for these we provide updates for future changes in the comment section. Our trades are divided into two separate tabs, option trades, and swing trades. The second idea behind our website is to provide users with tools for accurate predictions of potential profit and losses. So we took our favorite tools that we often use from other websites, built them ourselves and integrated them into our website for our users to us. When we did this, we looked for ways to improve upon these existing tools so that users would be more inclined to use our tools. One example of this is on our [Stock Profit Calculator](https://bncstocks.com/stock-profit-calculator/) where we auto populate the price based on the ticker the user entered. The last idea was to include a results page, as a benchmark for our website to gain credibility. In this page we post different charts and analysis of all of our trades. This was important to us especially for gaining trust from new users. 

# Software Development
The website was originally built with strictly JavaScript, HTML, and CSS ran on an Apache server that I had built on a spare raspberry pi I had lying around. I quickly realize that this was not the best solution for the longevity of our site. First, we needed a content management system, so that my partner and I could post easily and regularly. After doing some research, I decided that the Wordpress CMS would be the best for our situation. Next, we anticipate our website to eventually have a large community, and with a large community comes heavy traffic. A raspberry pi would quickly become very slow. After doing some more research, I found 
Bluehost, which is a web hosting service very easily integrated in Wordpress. We still use html and css to add details and formatting, as well as a lot of JavaScript for the tools and charts that we provide. We also recently added Google Adsense to the website as monetization was also a goal of this website. 

# Tools
As mentioned earlier we created the [stock profit calculator](https://bncstocks.com/stock-profit-calculator/) which allows the user to enter a stock, and easily calculate their potential profit or loss for a trade based on a few inputs. These inputs include # of shares, portfolio size, risk tolerance, target price and stop loss. Our calculator easily shows the user their profit/loss as well as how many shares of the stock to buy based on their portfolio size and risk tolerance. This makes our tool better than others available on the internet because it takes out mental calculations for the user and tells them exactly what they need to know before entering into a trade as well as auto-populating the current stock price using the yahoo-finance api. The other tool which is not yet complete, is the [options profit calculator](https://github.com/brandennevius/optionProfitCalculator) which you can click the link to see how it works in detail. This was another heavily used tool by my partner and I, and also has over 50,000+ views per month. So we are in the process of creating our own, and plan to add it to the website by the end of the year(2020). 

# To-Do
* We plan on adding an educational section where we provide informational posts so our users can learn the basics of stock trading as well as analyze our favorite strategies so our users can take what they learn from us and put it into practice on their own.  


