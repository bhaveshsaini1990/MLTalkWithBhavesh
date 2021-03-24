# MLTalkWithBhavesh

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Chapter 3 - Underfitting v/s Overfitting v/s Optimum Learning

Now again, instead of memorizing definition, let’s try to understand:


Boy 1: - His parents want their child to be independent. So, they gave him normal learnings and maximum times it’s his own responsibility to find solution for his problems, whether good or bad doesn’t matter because he even doesn’t know he is right or wrong (Such ML models have low accuracy during training time because model is not learning well on data/model is in underlearning phase).

Boy 2: - His parents want their child to be ready for all problems. So, his parents always suggest him what to do and what not to do in specific situations. That’s why he is able to handle all his problems in right way and in very effective manner (Such ML models have very high accuracy during training time because model have memorized data, so directly making decision according to that memorized information).

Boy 3: - His parents want their child to take right decision by himself in future. So, they are continously in touch with their child, when needed they are helping him but at the same time suggesting him also to take his own decisions based on learning (Such ML models have intermediate-high accuracy because it is taking decision based on his learnings and experiences till now).


After some years (After completion of Training phase, now its time for Testing phase where our ML model have to work against data which our model hasn’t seen yet/new data).


Boy 1: - Even don’t know what to do, because he is not trained enough to handle situations in right way. How to take right decision, so taking decision according to his experiences. (usually have low accuracy in Testing phase).

Boy 2: - Still don’t taking decision from his own mind but relying on what his parents had suggested him and taking decision according to that (have low accuracy in Testing phase).

Boy 3: - Using his mind while working on real time problem considering his past experiences as he already handled many situations till now (have intermediate-high accuracy in Testing phase).


Here, our Boy-1, Boy-2 and Boy-3 are three different ML models and Parents are representing the different ways of learning.

For example,

Boy-1 -> ML Model-1: - Training Accuracy=50% and Testing Accuracy=45%

Boy-2 -> ML Model-2: - Training Accuracy=98% and Testing Accuracy=60%

Boy-3 -> ML Model-3: - Training Accuracy=85% and Testing Accuracy=80%


Now understanding in single line,


Underfitting/Underlearning – Model working bad on Training as well as Testing dataset.

Overfitting/Memorizing – Model working good on Training dataset but again getting low accuracy in Testing dataset.

Optimum/Best fit/Optimum Learning – Model learning the actual scenario giving good comparable accuracy both in Testing as well as Training phase. 


For more detail refer this Article - https://towardsdatascience.com/underfitting-and-overfitting-in-machine-learning-and-how-to-deal-with-it-6fe4a8a49dbf

Feel free to share your feedback and suggestions on article.
Stay tuned for Chapter-4.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Chapter 2 - Ensemble modeling in Machine Learning


Case 1: - Suppose, you want to learn Java. But, you don’t know where to learn. So you discussed with friends and teachers. 


Friend 1: Go for YouTube channel Telusko Learning

Friend 2: Go for NPTEL Java course by Dr. Debasis Samantha

Teacher 3: Yes, go for NPTEL. They are from IIT and will explain in detail.

Friend 4: Don’t do Java. Just chill and enjoy life. Within 2 days we can pass Java exam.

So, as two of them said for NPTEL. So you finally decided to learn Java from NPTEL.
This is nothing but MaxVoting (a type of ensemble model).


Case 2: - You want to buy a plot at Pune in XYZ location. So you discussed 3 of your relatives in pune about cost estimation of plots in Pune.


Relative 1: It will cost you around 22 Lakhs

Relative 2: Around 15 Lakhs

Relative 3: May be around 20 Lakhs

So, simply you made average (22+15+20)/3=19 and estimated final cost of plots at Pune as 19 Lakhs.
This is known as Averaging (another type of ensemble modeling).


Case 3: - Suppose, you want to learn Java. But, you don’t know where to learn. So you discussed with friends, seniors and teachers. 


Friend 1: Go for YouTube channel Telusko Learning

Friend 2: Go for NPTEL Java course by Dr. Debasis Samantha

Teacher 3: Yes, go for NPTEL. They are from IIT and will explain in detail.

Friend 4: Don’t do Java. Just chill and enjoy life. Within 2 days we can pass Java exam.

Senior 5 (who is currently 7-star Java coder and working in Amazon as a Java developer): Start learning from Head First Java Book and do coding on HackerRank.

So, here in this case even NPTEL is recommended by two persons, you may go for Head First Java book along with HackerRank. But why? Because 5th person should be given more priority as he is currently in good stage in java field.
Here, you are simply doing Weighted Averaging (another type of ensemble modeling technique).


But now question comes that is these things related to Machine Learning?

Instead of making a single Machine Learning model for prediction. One can make different different models based on different different algorithms and analyze results of all models for giving final prediction. 
This is known as Ensemble Modeling (model accurany generally increases after using ensembling). 

In all of the above 3 cases, friends, relatives and teachers are nothing but our different different Machine Learning models which are giving their outputs, and we used ensemble techniques to maximize our accuracy.

Hope you understand the concept behind ensemble model. Stay tuned for Chapter-3

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ 	

# Chapter 1 - Introduction and AI in Gaming field


1. In 1997, Deep Mind's first computer to beat Gary Kasparov in Chess (one of the most broadcasted Chess game ever on planet at that time).

2. In March 2016, AlphaGo - it beat Lee Sedol in a five-game match, the first time a computer Go program has beaten a 9-dan professional without handicap (Go is popular game in Japan, korea, it is more complex than chess because possible combinations are high as compare to chess).

3. A team at Google DeepMind (who created AlphaGo), they saved 40% of electricity consumption after applying AI on Google warehouse to control Air cooling.


