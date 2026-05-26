1\. Weights and biases are the values that help the neural network learn from data.



Weights decide how important each input feature is for making predictions. For example, some customer details may affect churn more than others, and weights help the model understand that importance. Bias helps the neuron adjust its output and gives the model more flexibility while learning patterns.



**The basic neuron equation is:**



**y=wx+b**





During training, the model keeps updating the weights and biases to reduce errors and improve accuracy.







2\. Activation functions help the neural network learn complex patterns in the data.



Without activation functions, the neural network would behave like a simple linear model and would not be able to solve complicated problems like customer churn prediction.



Functions like ReLU and Sigmoid allow the network to decide which information is important and help it make better predictions.



**Example of ReLU:**



**f(x)=max(0,x)**



Activation functions basically make the neural network “smart” enough to learn non-linear relationships.





3\. The learning rate controls how quickly the model learns during training.



\-> If the learning rate is too high, the model learns too fast and may miss the correct solution. The accuracy may fluctuate   and the model can become unstable.



\-> If the learning rate is too low, training becomes very slow and the model may take a long time to achieve good accuracy.



Choosing a proper learning rate is important for getting better performance and stable training.





4\. The model did not show major signs of underfitting or overfitting.



The training accuracy and testing accuracy were reasonably close, which means the model was able to learn patterns properly and also perform well on new unseen data.



\-> Underfitting happens when the model cannot learn enough from the data.

\-> Overfitting happens when the model memorizes the training data but performs poorly on testing data.

