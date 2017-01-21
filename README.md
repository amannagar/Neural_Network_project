# Neural_Network_project
###Training and testing of muti layer neural network using theano framework in python
####exec_task1()
Fully Connected neural network with 3 layer of neurons, in which hidden layer is consist of 100 neurons and outer most layer of the network is consist of 10 neurons. Relu is used as the activation function of the hidden layer and is provided as input to the outer layer which has softmax as its activation function. Whole network is trained using the trained data which is images of dimensions 32X32, using which loss function graph w.r.t epochs (200) is made and error rate graph w.r.t  epochs is made as output of this task.
####exec_task2()
It is same as task 1, the only miner change is that we have to use sigmoid activation function in the hidden layer. Rest of the things are similar to the task 1 and same graph is required as the output but the plotting of the graph will be different due to sigmoid instead of relu in the activation function of hidden layer.
####exec_task3()
All we have to do in this task is to change the number of neurons in the hidden layer from 100 to 200 to 300 to 400 to 500 and plot the graph of error rate w.r.t hidden layer size.
####exec_task4()
We need to regularize weights in the network so that network recognizes the input image as correctly as it can. We are asked here to use value of lambda as 0.1, 0.2, 0.3, 0.4 and 0.5 and respectively train the network using training data set. In the output we need to make confusion matrix for all lambda values using test data set.
My code for training the weights and regularization of weights for all lambda value is running perfectly and training error is less than 10% for training data images but my confusion matrix is not getting correct due to some numpy data format precision error. So I would like to request you to look at the code and you can print epoch_wise_error variable then you would know that error is getting decreased. From 1000 images approximately 930+ images are correctly being identified so the error percent is approximately 6% – 7%.
####exec_task5()
Here considering all hyper parameters, the best parameters to train neural network efficiently and want it to recognize input images correctly are :-
•	Take activation function for hidden layer= sigmoid, because in the graph of it error rate its error rate is more less than relu’s
•	Take Lambda= 0.1, if weights are smaller then it will work more efficiently 
•	Take Number of neurons in the hidden layer= 500, because with increase in number of neurons in the hidden layer error rate decreases
Using all these best parameters we need to train the network using training data set of second data given and making loss function graph and error rate graph is same as task 1. And also making confusion matrix for test data. Note: All data set that is test data and train data containing images belongs to second data set.
