# Predicting Food Delivery Times with Machine vs Deep Learning

Note: See the final report for a more detailed explanation of the project's process, development, and results. The code in the appendices of the report is outdated, however. Since this project, I have gone back and made the code much more efficient and neat to more properly demonstrate my ability to write neat ML code.

This repository contains all of the files used and created as part of a data science challenge in Kaggle. 
link at https://www.kaggle.com/datasets/gauravmalik26/food-delivery-dataset?select=train.csv. 

In this challenge, participants were asked to take a dataset of 45,593 food deliveries with 20 features each and use it to train a machine learning algorithm and predict future delivery times. The dataset contained deliveries from all types of services, including independent service from a restaurant or grocer or third party food delivery companies. The data was entirely raw, thus requiring the participants to interpret it and clean it on their own. 

After cleaning and datamining the data, I decided that for my own entry, I would train a random forest regression model and a feedforward neural network. With both of these models, I could capture the nonlinear or discontinous relationships in the data that many other regression models could not. Furthermore, I also wanted to put the two models against each other and see which performed the best. Although complicated neural networks are fantastic for capturing very complex relationships in data or processing unconventional forms of data, they are more computationally expensive than random forest models as random forests' tree-based algorithms are much simpler than the neural network's neuron-based algorithms. Considering that this challenge's data was fairly straightforward, I had a premonition that the random forest model would perform just as well, if not better. 

In the end, the random forest regression model and feedforward neural network had testing R-squared values of 0.8431 and 0.8331, respectively. As I had predicted, the random forest model was not only up to par with its competitor, but it was also a little more accurate. Overall, this project gave me great experience in the full life cycle of data science. With the highest accuracy of any of the few, valid public entries, I can say I was happy with this project's outcome. Thank you for reading!
