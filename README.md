# 🎧 Thmanyah Podcast – Listener Insights

This assignment is all about understanding how people interact with Thmanyah’s podcast episodes. I was given three data files — users, episodes, and listen history — and asked to explore what we can learn from them.

## 💭 What I Did
I started by cleaning and combining the data. (the data was already cleaned from the beginning :) )

Then I dug into some questions like:

### Which categories are the most listened to?
- *The category with the highest number of listeners are: **Society** with a total of **32** listeners*

### What is the difference in the average listening time between males and females?
- *the difference in the average listening time between males and females: 3.01 minutes ( females listening time > males listening time )*

###  What is the average number of episodes listened to by one user? 
- *The Average number of episodes listened be single user: 5.26 (Note: we included the repeated listens to the same episode)*
- *The Average number of episodes listened be single user: 5.00 (Note: we excluded the repeated listens to the same episode)*

## A Simple Recommender
I also wrote a tiny function that recommends 3 episodes to a user based on the types they’ve enjoyed before using KNN Ai model.

🛠️ Libraries I Used
*gdown* for installing the files
*pandas* for data wrangling
*seaborn & matplotlib & plotly.express* for visuals
*sklearn.neighbors* for using KNN ai model
*random* to generate random recommendations, if the user is trying to use the platform for the first time  

### 🧠 Final Thoughts
It was an interesting assignment, and i enjoyed every part of it!
