# CristalloClassifier
Cristallo back-end API for second year project at University. 

# Purpose
This project is used to provide a transparent factor of authentication by receiving keystrokes from the client application
and converting them into heatmaps and feeding them into a Multi-Layered Perceptron classification algorithm. Given a small
amount of training data and multiple users, it can determine what user is trying to log in as who and can biometrically reject
people who it believes aren't who they say they are.

# Example
For an example case, say this was running in a small network with about 10 employees, each with unique typing patterns and
about 100 recognized and learned from heatmaps. Say Alice types fairly consistantly and it recognises Alice say about 9/10 times
every login attempt to account for a FAR(False Acceptance Rate). If Mallory came along, another employee at this company on the network,
looking to steal or view Alices' work on that particular machine. Mallory will not type like Alice unless she has learnt how she types. 
This program could distinguish if it truly is Alice trying to log-in or if someone else, in this case Mallory is trying to gain access.
