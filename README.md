Built With:
------------------------------------------------------------------------------------------------------------------------------------------------------------------
-Python 3.6.9
-Jupyter notebook


How to Run:
------------------------------------------------------------------------------------------------------------------------------------------------------------------

1.Run cell by cell until the training of the 5 classifier models then you either retrain them or load with pickle the models that are already trained , they are at the directory model.
2.Just see the results


Contributing:
------------------------------------------------------------------------------------------------------------------------------------------------------------------
Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are greatly appreciated.

Classifiers Included:
------------------------------------------------------------------------------------------------------------------------------------------------------------------
DecisionTree,
RandomForest,
Kneighbors,
Quadratic,
MLP

Dataset:
------------------------------------------------------------------------------------------------------------------------------------------------------------------
-Background:
-----------
The dataset to be audited was provided which consists of a wide variety of intrusions simulated in a military network environment. It created an environment to acquire raw TCP/IP dump data for a network by simulating a typical US Air Force LAN. The LAN was focused like a real environment and blasted with multiple attacks. A connection is a sequence of TCP packets starting and ending at some time duration between which data flows to and from a source IP address to a target IP address under some well-defined protocol. Also, each connection is labelled as either normal or as an attack with exactly one specific attack type. Each connection record consists of about 100 bytes.
For each TCP/IP connection, 41 quantitative and qualitative features are obtained from normal and attack data (3 qualitative and 38 quantitative features) .The class variable has two categories:
• Normal
• Anomalous
 
-Source:
-----------
https://www.kaggle.com/sampadab17/network-intrusion-detection

Prerequisites:
------------------------------------------------------------------------------------------------------------------------------------------------------------------
numpy,
seaborn,
pandas,
pickle,
matplotlib.pyplot,
sklearn,
warnings






Copyright (c) 2021 Dimitris Konstantakopoulos
