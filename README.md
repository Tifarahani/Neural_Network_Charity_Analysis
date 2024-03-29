# Neural_Network_Charity_Analysis

Overview of Project:
In this project by using knowledge of "Machine Learning" and Neural Networks, I created a binary classifier using features in the dataset that helps predict whether the applicants that will be funded by a Charitable organization called Alphabet Soup will be successful or not. For this analysis we had a dataset containing various measures on 34,000 organizations that have been funded by Alphabet Soup. This project compromised of the following 3 steps:

1. Preprocessing the data for the neural network
2. Compile, Train and Evaluate the Model
3. Optimizing the model
---

#### Deliverable 1: Preprocessing Data for a Neural Network Model

<p align="center">  
 <img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Drop_Ein%2CName.1.1.png" title="hover text">
</p>
<p align="center">  
<i>Figure 1: </i>
</p>

<p align="center">  
 <img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Unique_1.2.png" >
</p>

<p align="center">  
<img src= "https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Hot_encoder_1.3.png" >
</p>
       
<p align="center">  
<img src= "https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Split_1.4.png">
</p>              
      
<p align="center">  
<img src= "https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Fit_Scale_1.5.png" >
</p>
                 

#### Deliverable 2: Compile, Train, and Evaluate the Model
* Attempt 1: Removed additional feature, that is the 'USE_CASE' column. Rest of the model components stayed the same, however model accuracy went down to 68%.

<img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Attempt1.1.png">                                                        <img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Attempt1.2.png"> 


* The steps taken to try and increase model performance:

* Attempt 2: Adding Additional neurons to hidden layers and additional hidden layers are added. The accuracy went down again, this time it was 53%.    
                                             
<img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Attempt%202.png">   
<img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Attempt%202.2.png ">     
<img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Evaluate.Attempt%202.png">        
     
 *Attempt 3: Changing activation function of output layer from "sigmoid" to "tanh." The accuracy of the model went down even more to 50%.
     
 <img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Attampt%203.png"> 
 
 <img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Attampt%203.2.png">                                                                             
 <img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Attampt%203.3.evaluate.png">
 
---



#### Summary:
The model was not able to reach the target 75%. The accuracy for my model was 69%. There seems to be loss of accuracy after several attempt which is caused by overfitting the model.The model ended up with the accuracy score of 0.46 after optimization.
we could further also optimize our neural network by removing more features or simply adding more data to the dataset to increase accuracy. Since our accuracy score was not particularly up to the standard with neural networks, we could have used the Random Forest classifiers. 


