# Internship_Work
WorkDone at Infilytics


This repo is containig the work, I have done during my internship.
Problem Statement: Predict Sales for Today in morning(let's say) and compare today's sales value at the end of day. Now, If company has made sales a lot more/less 
than predicted value then make conclusions from it. 
---------------------------------------------------- OR -----------------------------------------------------
Find Data points where company have done less sales then trend or more then trend and display those dates then company can run their analysis on it.

At very first, I preprocessed the data and get through it once.
Now as a starter, I made model with basic ML algos like Linear Regression, Random Forest etc. Now, I've got one base model and some accuracy. Now I need to beat that score and do some imporvisation.
From base model, I learn that best lockback period is 7 days.
After that, I googled about in which category this problem statement falls in. More or less this problem falls under the category of Time Series Analysis(Regression).
Then I searched for the model which would work for Time series analysis. In most of the search, I've got ARIMA model. So I started learning about it.
After some days of learning and understanding the model, I made predictions from that model. This model was providing good accuracy and it was able to find data points.
Now, For big company which is making thounds of transection in a day. ARIMA model returns a perticular date and then company can do analysis on data and find where they did poor or good. 
Now returning a perticular date and do analysis on it is also not possible company as there are hundreds of transaction in a day. So, by adding a parameter we need to narrow down their search.
Now, ARIMA model works only on date and sales value. One can't add any more feature in it. That is why we need to leave that model.
One of my friend suggested that this problem statement can't be solved only with ML. You need to apply Deep Learning concepts for it.
As Deep learning is a vast field and to make model on your own you need to understand the concepts of it. So, I spent a week learning it.
Then by Tweaking model, I found parameters which gives good results for given data.
Now, By RNN model I was able to beat accuracy of ARIMA model and this model was able to provide dates more precisely which have more/less sales data then trend.
Then, to make search of company narrower, I tried to add one paramter(Customer_ID). And I trained same model on that strucutre. This model was not able to give that much accuracy.

Start Working from- 
Find model which gives better results by adding one parameter and give specific date & parameter to search for.
