# Handmade-Neural-Network
A vanilla Neural Network made from scratch using numpy libraries mostly to classify numbers in the number system,  used matplotlib for visualisations

- I made this network only to classify numbers because i thought well if they can classify handwritten digits then why not numbers, and i decided to only classify 10 because well it's perhaps has the most distinctive feature of being recognised from other numbers. 

- If 1 is passed as the thresh parameter in the setup fucntion, i simply wish to see the activation function of final layers as to where do they light up exactly, and if any other number other than 1 is passed as thresh it is used as a threshold for classifying numbers.

- I saw some crazy distributions of training classifications(while passing the thresh as 1) which i didn't classify, because it didn't make sense to classify them

- in some matrix multiplications like in the backward pass , i pass the transpose of weight matrix instead of weight matrix to facilitate matrix multiplications, the concept reamins the same though.

- my test and training dataset for the graphs present there is between 100 to 999, but yea i have tried also for numbers between 1000 and 7000 and well it somewhat works

- This happens to be a very very raw neural network from scratch so yea there definitely would be rookie mistakes, i am very much welcome to suggestions, and yes i did not try hard to get the right number of epochs or batch numbers, so yes accuracy isn't a very promising part, I wanted mostly to build it from scratch.

- I used a lot of free tutorial out there while making it particularly from here :

+ https://medium.com/binaryandmore/beginners-guide-to-deriving-and-implementing-backpropagation-e3c1a5a1e536
+ http://neuralnetworksanddeeplearning.com/chap2.html
+ https://towardsdatascience.com/lets-code-a-neural-network-in-plain-numpy-ae7e74410795


