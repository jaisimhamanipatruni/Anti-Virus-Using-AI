# Anti-Virus-Using-AI
Anti-Virus Using AI 

Antivirus Demo
Overview
This project helps train a classifier to be able to detect PE files as either malicious or legitimate. It tries out 6 different classification algorithms before deciding which one to use for prediction by comparing their results. This is the code for 'Build an Antivirus in 5 Min'.

Dependencies
pandas pip install pandas
numpy pip install numpy
pickle pip install pickle
scipy pip install scipy
scikit pip install -U scikit-learn
Use pip to install any missing dependencies

Basic Usage
Run python learning.py to train the model. It will train on the dataset included called 'data.csv'.

Once trained you can test the model via python checkpe.py YOUR_PE_FILE. It will output either malicious or legitimate!

That's it!
