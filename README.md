# DF Capstone Premier League Player Sale Predictor
My final capstone project for Digital Futures looks into Premier League Players and whether, based on their performance stats, they should be kept or sold by their club. 

## Description:
It is a tough role for any manager in football, but sometimes, players need to be sold. If a player is underperforming, the club may need to relieve them of their duties. But how can we tell if a player is underperforming? 
A good way to do this is by using the amazing power of hindsight to see what players were sold by their club in a previous season. Then, we can observe certain stats to essentially determine the expected stats of a player who ended up being sold by their club.
By using a process known as Logistic Regression, a model can be created for multiple uses to determine whether a player should be sold or kept by a club based on certain stats.
The stats used for this project are those that were available in the dataset containing stats for every Premier League player in the 18/19 season. 

## Conclusions:
The accuracy of the Logistic Regression Model would be identified by the Test Accuracy of the Confusion Matrix. The test accuracy was 83%; meaning that the model is accurate 83% of the time. 83% is a great accuracy for this model, but it could have been improved by including other variables in the model. However, the reason that some variables were excluded is because they would have high P-Values; which is essentially the model saying that the variable isn't very helpful. Therefore, to prevent the accuracy from being unreliable, these variables were removed from the final model.

## Improvements:
An ideal improvement would be to work with more stats. The stats used in the model were useful, but having more would produce a more reliable model. 
Moreover, it should be understood that being poor statistically is not the only reason a player would be sold. For example, although a more rare feat, a player will be sold if they vastly outperformed others statistically. Since this is rare, a model that determines whether a player should be sold based on their stats would naturally assume that this outperforming player should be kept; when in reality, they were sold. 
A good example of this is the Crystal Palace player Aaron Wan-Bissaka, who was predicted by the model to be kept because he performed well, but was sold to Manchester United to gain a monetary capitalisation on his good performances. 
##
This repository contains the Capstone Project Notebook, a Requirements file and the Capstone Presentation Slides. 
The data set used in this project can be found on https://footystats.org/c-dl.php?type=players&comp=1625
## Capstone Project Video:
https://user-images.githubusercontent.com/92789215/145447805-b9a156f4-0f1a-4532-a0cb-61b0dbe08897.mp4
