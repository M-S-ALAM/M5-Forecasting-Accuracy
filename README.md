# ${\color{green} M5 \ Forecasting \ Accuracy}$

Machine Learning/Time Forecasting
# 1.Business Problem

### 1.1 Problem Description

### 1.1 What is sales forecasting?
<pre>The technique of anticipating future sales, either short- or long-term, using previous sales data is known as sales forecasting.</pre>


### Problem Statment:-

<pre>For instance, investing in new strategies to improve their revenue for their items that may account for poor sales in the future through promotions/discounts e.t.c., forecasting sales is crucial for the companies. Therefore, it becomes crucial for established businesses to make realistic sales projections for the future.</pre>

### 1.2  Features in the Dataset
<pre>
Source:-[https://www.kaggle.com/sherinclaudia/sarcastic-comments-on-reddit](https://www.kaggle.com/competitions/m5-forecasting-accuracy/data)</pre>
## 1.3 Source
<pre>
<li> https://www.kaggle.com/sherinclaudia/sarcastic-comments-on-reddit </li>
<li> https://www.kaggle.com/asifranaar/sarcastic-comments-eda-and-classification </li>
<li> https://medium.com/@roy.aditya1605/reddit-sarcastic-comment-detection-dc665d8d21b9 </li>
<li> https://www.kaggle.com/yudhagalang/lstm-text-classification-on-reddit-sarcasm </li>
<li> https://arxiv.org/pdf/1610.08815.pdf</pre>
## 1.4 Bussnies Objective and Constraints:-
<pre>Data is provided by kaggle https://www.kaggle.com/sherinclaudia/sarcastic-comments-on-reddit,to predict the comment is sarcastic or non sarcastic.This problem is classification problem(Supervised Learning).The features we have in train data label,author,comment,ups,downs,score, subreddit,created_utc,parent_comment.

<li> High Interpret ability since we must understand the crucial factor that contributed to good predictions.</li>
<li> No rigorous low latency is required because we need to forecast sales daily rather than minute by minute or hour by hour.</li> </pre>
##  2.Machine Learning Problem
<pre> We need to categorise a given data point into one of two classes indicating whether the statement is sarcastic or non sarcastic.This is Binary classification Problem.</pre>

### 2.2 Example Data Point
<pre> 0,NC and NH.,Trumpbart,politics,2,-1,-1,2016-10,2016-10-16 23:55:23,"Yeah, I get that argument. At this point, I'd prefer is she lived in NC as well."
-------------------------------------------------------------------------------------------------
0,You do know west teams play against west teams more than east teams right?,Shbshb906,nba,-4,-1,-1,2016-11,2016-11-01 00:24:10,The blazers and Mavericks (The wests 5 and 6 seed) did not even carry a good enough record to make the playoffs in the east last year.
-------------------------------------------------------------------------------------------------
0,"They were underdogs earlier today, but since Gronk's announcement this afternoon, the Vegas line has moved to patriots -1",Creepeth,nfl,3,3,0,2016-09,2016-09-22 21:45:37,They're favored to win.</pre>
### 2.3 Type of Machine Learning Problem

<pre> We need to categorise a given data point into one of two classes indicating whether the statement is sarcastic or non sarcastic.This is Binary classification Problem.</pre>
### 2.4 Performance metric
<pre> 
<li>Confusion metric </li> 
<li>Accuracy</li></pre>

### Blog link:-https://medium.com/@mdshahbazpatna012/sarcastic-comments-detection-reddit-an-end-to-end-case-study-e0de7fb275a4
