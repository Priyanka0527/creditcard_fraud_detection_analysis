# FRAUD DETECTION SYSTEM USING NEURAL NETWORKS

Motivation and Problem Description :
<br>
Credit card fraud is a serious problem that inflicts considerable financial loss on both institutions and 
customers. The central agenda of the issue is in the necessity to identify fraudulent transactions properly, on 
time and correctly in data that is naturally imbalanced—only a very tiny fraction of total transactions are 
fraudulent cases and the data imbalance presents a serious challenge since standard classifiers are usually 
swamped by the majority class, which results in high misclassification rates for the minority (fraud) class. By 
detecting fraudulent transactions in a timely manner, the system not only avoids losses but also improves 
security and trust within digital financial systems.

Approach : 
<br>
To tackle the above mentioned challenges, our project leverages neural network models with a focus on two 
principal components: 
1. Data Preprocessing and Balancing: 
•  Begin by normalizing the dataset using standard scaling to ensure that all features contribute    
equally to the model's learning process.  
• The StandardScaler is a preprocessing technique used in machine learning that standardizes the 
features of a dataset by transforming them to have zero mean and unit variance. This ensured that 
all the features contribute equally during model training and prevents certain features with larger 
values to dominate the learning process.  
• Then , after recognizing the highly imbalanced nature of credit card transaction data, we use 
oversampling techniques to balance the dataset. This ensures that the model receives a proportional 
representation of fraudulent (1) versus legitimate cases (0), thereby improving the model’s capacity 
to generalize and detect rare events. 
2. Model Building and Evaluation: 
 • Then construct a neural network with two hidden layers, experimenting with different activation 
functions—specifically, tanh and ReLU. The output layer uses a sigmoid activation function to enable 
probabilistic classification between fraud and non-fraud classes .
• Then compile the model with various optimizers like SGD, Adam, and RMSProp to understand 
how different gradient descent methods affect performance. This multi-pronged strategy acknowledges 
that various optimizers might handle the same loss landscape differently, particularly in the presence 
of an imbalanced dataset. 
• The network is trained on the preprocessed dataset and evaluated using a classification report focusing 
on metrics like precision, recall, and F1 score. Then graphical plots are used to visualize the 
performance differences between the various activation functions and optimizers, providing practical 
insights into which combination yields the best trade-off in detecting fraudulent transactions. 
1.3 Basic Results and Conclusions : 
Activation functions and optimizers work together to achieve optimal detection rates for fraudulent 
transactions, according to our initial evaluations using our neural network model. The classification reports 
produced for various configurations provide specific proof of how each setting affects performance by 
highlighting differences in the different performance metrics, such as accuracy, precision, recall, and F1-score. 
Additionally, we can identify the most promising approaches for further refining the neural network model 
thanks to the graphic representations of these results. 



