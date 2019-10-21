Goals:
In image recognition or speech recognition applications, the computational complexity of the deep neural network model is very large, and there is a certain data correlation between layers of the model. Therefore, how to divide the task amount and computing resources is an important issue for the design of CPU or GPU cluster acceleration framework. When the scale of the trained model is relatively large, the training of the model can be accelerated by the data parallelism method.

Pros:
The error rates of the serial BP algorithm and Map-Reduce-BP algorithm are at the same level and are within acceptable error range. At the same time, the cloud computing clusters costs less time and fewer times of iterations, which means that the Map-Reduce-BP algorithm is more efficient. 

Cons:
(1) The versatility of MapReduce is not very good, and it is not adaptable in many data processing scenarios. 
(2) The operation of Reduce part needs to wait until most parts of Map complete their operations. In some cases, when the distribution of computing is uneven, Map operations will cost a long time and Reduce operation will wait for the complete of Map operation. 
