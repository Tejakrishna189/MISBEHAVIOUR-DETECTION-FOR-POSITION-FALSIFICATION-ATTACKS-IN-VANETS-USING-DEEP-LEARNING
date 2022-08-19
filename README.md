# Misbehaviour-detection-for-position-falsification-attacks-in-VANETs-using-deep-learning

Dataset which I used for this project is from https://github.com/VeReMi-dataset/VeReMi/releases
Open the above link and download all the 225 simulations and then extract them now click on each simulation then you will find a folder named result copy that folder now create a new folder name it data now paste that copied folder into the dataset folder repeat the same process for all remained simulations
After extracting results from all the 225 simulations now apply the dataset.ipynb code which I uploaded in the working code folder change the paths to respective paths where you saved the data folder
Now by  applying the k means algorithm which I uploaded in the working code folder we get clusters that gives us attacker type and attacker position
And then we use the gaussian mixture model to reduce the colliding in clusters and it is used to maximize the result this code is uploaded in the working code folder

Intelligent Transport Systems (ITS) are information systems that aim to 
reduce traffic congestion and improve road safety. Vehicular Ad-hoc 
Networks (VANETs), a subsystem of Intelligent Transport Systems (ITS) 
enable vehicles to have effective communication through wireless networks 
to provide safety and to monitor traffic conditions. The security of VANETs 
and their data is crucial. Attacks may occur in such networks reducing their 
efficiency and endangering the passengers' safety.
An Intrusion Detection System (IDS) is introduced in VANETS to facilitate 
secured transactions among the V2V communications, which will detect the 
vehicles sending false positioning data in their transactions. These 
misbehaving vehicles are classified as anomalies and have to be cautious 
with such communications. Hence, we propose a deep learning-based 
anomaly classification mechanism to detect if any of the nodes in the 
vehicular networks are misbehaving. We propose to train the model with 
two features majorly related to the sender position, which classify the 
anomalous behavior in the vehicle's communications.
