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
 <img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Unique_1.2.png" " title="hover text">
</p>

<p align="center">  
<img src= "https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Hot_encoder_1.3.png" "title="hover text">
</p>
       
<p align="center">  
<img src= "https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Split_1.4.png"  title="hover text">
</p>
                 
      
<p align="center">  
<img src= "https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Fit_Scale_1.5.png"  title="hover text">
</p>
                 
<p align="center">  
 <img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Define_Layers_2.1.png"  title="hover text">
</p>

#### Deliverable 2: Compile, Train, and Evaluate the Model

<img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Define_Layers_2.1.png" title="hover text">
<img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Compile_2.2.png title="hover text">

* Attempt 1: Removed additional feature, that is the 'USE_CASE' column. Rest of the model components stayed the same, however model accuracy went down to 63%.
                                                                                                                                 
* Attempt 2: Adding Additional neurons to hidden layers and additional hidden layers are added. The accuracy went down again, this time it was 53%.    
                                                                                                                                                               
<img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Attempt%202.png">                                              
<img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Attempt%202.2.png ">                                                                                                                               
 *Attempt 3: Changing activation function of output layer from "sigmoid" to "tanh." The accuracy of the model went down even more to 50%.
                                                                                   
  <img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Attampt%203.2.png">                                                                             
 <img src="https://github.com/Tifarahani/Neural_Network_Charity_Analysis/blob/main/Resources/Img/Attampt%203.3.evaluate.png">
 
---
#### Resources:
