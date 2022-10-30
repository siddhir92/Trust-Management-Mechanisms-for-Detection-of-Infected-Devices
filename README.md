# Trust-Management-Mechanisms-for-Detection-of-Infected-Devices 💻- Final Year Project For my coursework
Detection of Infected Devices in IoT using ML Algorithms
<h2>Objectives </h2>

<li> We use three machine learning algorithms Random Forest, Multilayer Perceptron and Autoencoder. </li>
<li>Based on the literature survey, it has been found that a supervised as well as unsupervised model can be used in the detection of infected devices thus, we use the above three algorithms.</li>
<li>The dataset which was found needs to be properly processed along with normalization and standardization of data.</li>
<li>The dataset is combined together to make a new dataset consisting of balanced data.</li>
<li>Then we apply two classification algorithms such as Random Forest as well as Multilayer Perceptron to find the accuracy of our model to find the infected devices.</li>
<li>We then utilize the Autoencoder which is an unsupervised learning algorithm to teach our model the features which make up a normal device and then test on a dataset full of infected devices to check if it is able to identify them.</li>

![image](https://user-images.githubusercontent.com/64797270/198870626-6eef3a4b-9012-481d-bbcb-0b6094b7e7ea.png)

<h2> Flowchart </h2>

![image](https://user-images.githubusercontent.com/64797270/198870612-d8db0431-a125-4acc-834f-b5f65745d240.png)

In this project we are calculating the accuracy and recall values for the three different machine learning models: MLP, Random Forest and AutoEncoder
<h3>Results</h3>

MLP Model👇
![image](https://user-images.githubusercontent.com/64797270/198870824-df8a50c5-3d88-424f-97c9-eb29f38c1189.png)

Random Forest Model👇
![image](https://user-images.githubusercontent.com/64797270/198870838-5787d018-39a7-48ae-88e3-59b9679596ff.png)

Auto Encoder Model👇
![image](https://user-images.githubusercontent.com/64797270/198870852-33e53eb5-c424-469d-ba56-4b93aa834969.png)

![image](https://user-images.githubusercontent.com/64797270/198870944-ecc49609-e12a-4b4e-b099-711c9fdd3ec2.png)
![image](https://user-images.githubusercontent.com/64797270/198870951-5a00960c-9321-486d-adfc-96cef9481df0.png)


We choose Botnet attack which can perform Distributed Denial of Service Attack (DDoS) on the nodes. The reason why we choosed this attack is that, DDoS is a very common attack which can be performed on any application. In particular, we targeted Mirai and Bashlite malwares which are based on botnet attack. We have considered three algorithms, Multi-layer Perceptron, Random Forest and Autoencoder to train our model. With each model we observed different accuracies in detecting the infected devices. As a result, Autoencoder model was the one which was able to detect maximum number of anomalies and that is more suitable for our trust model.  

<h2>Future enhancement </h2>

This model was successful in detecting the infected devices from botnet attacks, the next step for this model is to actually deploy it in a network-based environment where it can detect real-time attacks. Further studies need to be done to incorporate hardware devices if it can be used in detecting the anomalies which would make our model more robust. 
