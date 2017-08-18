---
layout: post
title: Predicting Domestic Box Office Gross
---
#### Why We Care?
Although US has the most success movie business, it still suffers from high failure rate. An analysis of almost 5,000 movies since 1980 shows that nearly *one of three* movies have failed. In addition, the average cost of making a movie is as high as 33 millions, for the most successful movies, the cost is even higher. With the high failure rate and high cost, it is critical for investors to know how much money they can potentially make before they commit to such huge investment upfront.
#### How I Help?
I am trying to help address movie investors' concern by building up a linear regression model to predict domestic box office. Linear regression model is a simple yet powerful tool when it comes to make predictions. A typical linear regression looks like this:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![alt text](https://siyuan126.github.io/images/multi-regression-equation.png)

As long as we figure out all the parameters in the model, we give this model a series of input, we will get an output. Thus we can use this model to predict futuren domestic box office. 

#### What I do?
I use popular web scraping tools beautifulsoup and Scrapy to extract data from two websites : [MojoBoxOffice]( http://www.boxofficemojo.com) and [The Numbers](http://www.the-numbers.com). In total, I collect 12 features of 514 movies from 2009-2016. 
