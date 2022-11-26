# Hotel-Booking-Demand
## __A. Problem Background__
Last-minute cancellations of hotel bookings have increased in recent years. Many factors can affect the cancellations, including changes to meeting schedules, changes to holiday schedules, bad weather conditions, and various other factors. Identification by [Chen and Xie (2013)](https://drive.google.com/file/d/1yIRYqXT0pyztsBjNTc9Y68Y3g68KlSup/view?usp=sharing) and [Chen, Schwartz, and Vargas (2011)](https: //daneshyari.com/article/preview/1010016.pdf), currently most customers cancel because they want to get the best price. Sometimes after placing an order, the customer continues to search further for the same product/service that has been ordered. As a result, customers will place orders for all of these products/services then cancel at the last minute and leave the best one. This is the impact of the digital technology which makes it easier for someone to make reservations and cancel rooms.

The easier access to book and cancel hotel bookings causes hotels to lose cost. Thus, this phenomenon becomes one of the factors used by managerial in making a policy. One way is to implement policies that are quite rigid. In addition, the managerial also applies policies such "charge or deposit" that must be paid by customers when canceling the bookings [(reference)](https://pdfs.semanticcholar.org/f468/aaa140f7c1eb7aa37b9bca495ae76b82f654.pdf). The policies implemented can have a negative impact on the reputation and performance of a hotel in the future because customers will prefer hotels that can be easily cancel and without being charged.

## __B. Project Goals__
This project offers a solution to the problem that occurs. A *machine learning* program will be built so that business owners can predict whether the person will cancel or not when make a booking. This project will use historical data that has been collected from several hotel management parties around the world ([data source](https://drive.google.com/file/d/12uB4vKhUUQj3brmQ4N7zfw8BwLYvfqzb/view?usp=sharing)). Thus, with these predictions, policy basis for the decisions can be made by managerial.

## __C. Model Limitation__
This program is limited to the data provided. Therefore, it is very possible that there will be differences in results with other program with the same model.

## __D. Model Algorithm__
- Logistic Regression, KNN, Decision Tree, Random Forest

## __E. Summary__
Based on the model results above, it can be concluded that :
1. Machine learning model that be used are Logistic Regression, Decision Tree, KNN, dan Random Forest
2. Matrics Evaluation that be used is ROC AUC 
3. From the classification report, there are : 
  - The model can minimize wrong prediction, guests who cancel but are considered not to have canceled (recall score). In this case, the model is able to predict 94% of guests who do not cancel hotels and 53% of guests who do hotel cancellations. So there are 6% of guests who cancel but are considered not to have canceled
  - The model can minimize the guests who do not cancel but are considered to have canceled (precision score). The model is able to predict 83% of guests who cancel.
