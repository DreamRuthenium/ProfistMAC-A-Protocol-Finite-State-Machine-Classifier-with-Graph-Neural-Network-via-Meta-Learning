# ProfistMAC-A-Protocol-Finite-State-Machine-Classifier-with-Graph-Neural-Network-via-Meta-Learning
A demonstrative code for the paper"ProfistMAC: A Protocol Finite State Machine Classifier with Graph Neural Network via Meta-Learning"

# Quick Setup
1. Run gen_image.py to transform .pacp files into .csv files
2. Run Graph_generation_trans.py to transform .csv files into traning data
3. Train the model in Model_trans.py(you need a pre_trained model for the transform learning)
4. Run Test_trans.py to test the model.

# TroubleShoot
### How to split the .pcap files?
You can use your own rules like recognizing flows by IP addresses, or use splitcap.exe, which is easier.
