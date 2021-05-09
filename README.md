# Neural_Network_Charity_Analysis
## Overview
Alphabet soup co wants to create a intelligent model which can predict whether the Non profit org can screen applicants well in advance if they will be successful  in the ventures funded by them.
With an intelgient help of Neural network model and Machine learning i was able to analyse the features in the data to create a binary classifier that will be capable to predict whether applicants will be succefful if funded by Alpaheb soup co. 

I further fine tuned the model to reach the maximum efficency and accuracy.

## Click [here](https://github.com/josephthomas08/Neural_Network_Charity_Analysis/blob/main/AlphabetSoupCharity.ipynb) to check my Jupyter notebook for Delverable 1 & 2.

## Results 




## Deliverable 1.0: Preprocessing Data for a Neural Network Model


### The following preprocessing steps have been performed:
#### D 1.1 The EIN and NAME columns have been dropped 

The EIN and NAME  variables was dropped from the analysis because they are neither Features nor Target for the model creation:



<img width="1026" alt="D1 1 Module 19" src="https://user-images.githubusercontent.com/75267605/117582577-a00fac80-b0d0-11eb-9bcd-e7b6f1533ba0.png">



#### D 1.2 The columns with more than 10 unique values have been grouped together 

<img width="595" alt="D1 2 Module 19" src="https://user-images.githubusercontent.com/75267605/117582581-a3a33380-b0d0-11eb-8c16-4ba86c31be40.png">


#### D 1.3 TThe categorical variables have been encoded using one-hot encoding 


<img width="1022" alt="D1 3 Module 19 " src="https://user-images.githubusercontent.com/75267605/117582585-a69e2400-b0d0-11eb-8b3f-f67094b17b36.png">


#### D 1.4 The preprocessed data is split into features and target arrays and D 1.5 The preprocessed data is split into training and testing datasets 

<img width="939" alt="D1 4-5 Module 19" src="https://user-images.githubusercontent.com/75267605/117582588-ab62d800-b0d0-11eb-9335-d636f64d8396.png">


#### D 1.6 The numerical values have been standardized using the StandardScaler() module 

<img width="661" alt="D1 6 Module 19" src="https://user-images.githubusercontent.com/75267605/117582596-b74e9a00-b0d0-11eb-99ba-1ec2aacadf45.png">

## Deliverable 2.0 : Compile, Train, and Evaluate the Model


### The neural network model using Tensorflow Keras contains working code that performs the following steps:
#### D2.1 The number of layers, the number of neurons per layer, and activation function are defined and D2.2 An output layer with an activation function is created & D2.3 There is an output for the structure of the model 

<img width="994" alt="D2 1-3 Module 19" src="https://user-images.githubusercontent.com/75267605/117586393-e0c5f080-b0e5-11eb-8896-26f501f17bea.png">


#### D2.4 There is an output of the model’s loss and accuracy 


<img width="688" alt="D2 4 Module 19" src="https://user-images.githubusercontent.com/75267605/117586397-e4f20e00-b0e5-11eb-8d72-756a25231716.png">


#### D2.5 The model's weights are saved every 5 epochs 


<img width="777" alt="D2 5 Module 19" src="https://user-images.githubusercontent.com/75267605/117586399-e8859500-b0e5-11eb-8a8a-ef49da271e6a.png">


#### D2.6 The results are saved to an HDF5 file 



<img width="465" alt="D2 6 Module 19" src="https://user-images.githubusercontent.com/75267605/117586403-ed4a4900-b0e5-11eb-926b-7529e36363b8.png">




## Deliverable 3: Optimize the Model

## Click [here](https://github.com/josephthomas08/Neural_Network_Charity_Analysis/blob/main/AlphabetSoupCharity_Optimzation.ipynb) to check my Jupyter notebook for Delverable 3.

### The model is optimized, and the predictive accuracy is increased to over 75%, or there is working code that makes three attempts to increase model performance using the following steps:
#### D3.1 Noisy variables are removed from features 

<img width="1002" alt="D3 1 Module 19" src="https://user-images.githubusercontent.com/75267605/117588184-db6da380-b0ef-11eb-9b99-96ba0cfc40bf.png">


<img width="756" alt="D3 1 A Module 19" src="https://user-images.githubusercontent.com/75267605/117588178-d0b30e80-b0ef-11eb-88de-e046b3050f99.png">


<img width="682" alt="D3 1 B Module 19" src="https://user-images.githubusercontent.com/75267605/117588192-ede7dd00-b0ef-11eb-9482-6027422f85a7.png">

#### D3.2 Additional neurons are added to hidden layers 


<img width="838" alt="D3 2 Module 19" src="https://user-images.githubusercontent.com/75267605/117588202-f8a27200-b0ef-11eb-9797-11e27d1d3eab.png">


<img width="701" alt="D3 2 A Module 19 " src="https://user-images.githubusercontent.com/75267605/117588204-fd672600-b0ef-11eb-8e26-bdf3b5a2d67e.png">

#### D3.3 Additional hidden layers are added

<img width="794" alt="D3 3 Module 19" src="https://user-images.githubusercontent.com/75267605/117588210-022bda00-b0f0-11eb-8195-82aed5032cc3.png">

<img width="738" alt="D3 3 A Module 19 " src="https://user-images.githubusercontent.com/75267605/117588218-0b1cab80-b0f0-11eb-86cb-61c932c24058.png">


#### D3.4 The activation function of hidden layers or output layers is changed for optimization

<img width="992" alt="D3 4 Module 19" src="https://user-images.githubusercontent.com/75267605/117588276-5e8ef980-b0f0-11eb-9539-79d13401db82.png">


#### D3.5 The model's weights are saved every 5 epochs


<img width="778" alt="D3 5 Module 19" src="https://user-images.githubusercontent.com/75267605/117588315-8d0cd480-b0f0-11eb-96be-4b27e460e872.png">


#### D3.6 The results are saved to an HDF5 file 


<img width="619" alt="D3 6 Module 19" src="https://user-images.githubusercontent.com/75267605/117588278-62228080-b0f0-11eb-8771-c2a2520d0452.png">



## Deliverable 4: A Written Report on the Neural Network Model


## SUMMARY
As detailed above, various attempts and  measures were taken to improve the accuracy from 70% which included changing the noisy variable, increasing/decsreasing the neaurons, adding additional hidden layers, keeping only one hidden layer, changing the output layer activation function but it was realized that the accuracy could not be  increased beyond  70%.

The data set with 34000 data points though looks higher it is still  on a lower side from deep learning neuron model point of view hence it  would be recommended  to use "Random Forest" which is faster and is more appropriate for this size of a dataset.





