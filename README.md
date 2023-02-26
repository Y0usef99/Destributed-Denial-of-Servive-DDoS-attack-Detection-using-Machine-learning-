# Thesis scope

   In this paper, I used the dataset CIC-DDoS2019 from the Canadian Institute of 
Cybersecurity (CIC) [6].

   I. Sharafaldin et al. [7], created a new dataset, called CICDDoS2019. This dataset 
addresses all present inadequacies. They have also offered a new detection and family 
classification strategy based on a collection of the network flow characteristics, which they have 
realized while utilizing the produced dataset. Finally, they presented the most significant feature 
sets for detecting various forms of DDoS assaults together with their weights.
 The dataset has been fully labelled with 80 network traffic features collected and 
computed for all benign flows and denial of service attacks flows.


Dataset: https://www.unb.ca/cic/datasets/ddos-2019.html

   In this paper, I will only be using NetBIOS, LDAP, PORTMAP and MSSQL from the 
reflection based attacks, and all the “exploitation based” attacks which are UDP, SYN and UDP-Lag


   Data Preprocessing:

   Data pre processing is the process of converting raw data into a proper format of data by 
refilling incomplete data and deleting inconsistent, redundant, or noisy data. Several procedures 
are done on the data to minimize dimensionality and preserve consistency for simplicity of 
processing. The mentioned stages below were engaged in the data pre-processing stage.

• Managing Null Values
• Handling Categorical Data
• Calculating the Standard Deviation
• Examining Correlation
• Dataset Standardization
• Dealing with outliers

  My Proposed approaches:

   I have proposed 3 different models. In model 1, the model is capable of detecting whether 
the incoming packet is an attack or not and if so it classifies the type of attack. In this model I’ve 
used Convolutional Neural Networks (CNN) for the detection and classification of the DDoS 
attacks.
 

  In Model 2, the model is also capable of identifying weather the incoming packet is an 
attack or not and classifying the type of the attack. I’ve used in this model deep neural networks 
(DNN).


   In Model 3, the model proposed is capable of only identifying while the incoming 
packet is an attack or not without applying any sort of classification. I’ve also used in this model 
deep neural networks (DNN).

