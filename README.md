# Titanic
The sinking of the RMS **Titanic** is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.


          
![](https://user-images.githubusercontent.com/34382779/38109879-2d76652c-33b7-11e8-865b-ece7088274de.jpeg)  |  ![](https://user-images.githubusercontent.com/34382779/38109897-476fa056-33b7-11e8-8b7b-49738875d9fc.jpeg)


This is prediction of what sorts of people were likely to survive. In particular, machine learning algorithm(neural network) is applied to classify survived passengers.

Model is trained on training data of 891 passengers that includes :-
* PassengerId  
* Survived     
* Pclass       
* Name          
* Sex           
* Age            
* SibSp        
* Parch        
* Ticket        
* Fare           
* Cabin         
* Embarked  


The visualization shows that passengers survived are females and passengers with pclass 1 and 2 than 3.Therefore model is trained with Pclass and Sex as input and Survived as output.
This code uses the **keras library with Tensorflow backend.**
Other library used are--
* pandas
* numpy
* matplotlib

Data is available on https://www.kaggle.com/c/titanic
