Sign Language Detection Deep Learning Implementation

This repository contains the code required to implement a live stream translation of sign language based on words provided Google's Isolated Sign Language competition in Kaggle (https://www.kaggle.com/competitions/asl-signs)

The program use MQTT to communicate between the signer_no_mediapipe.py (or signer_with_mediapipe.py) and ML_model.py files in order to pass the video frames and then provide a live translation of the word signed. 

Note: This program can only translate single words at this time and cannot translate sentences. 

In order to use the program and translate sign language words, the user has to start the control sequence by pressing the 'Spacebar' and then stop the control sequence by pressing 'Spacebar' again. Any word signed between this is translated by the model + camera interface.

The TFLite model is important as this processes the words signed and then translates them. 
Edge device implementation was completed as part of class project at UC Berkeley, MIDS - 251 Deep Learning in the Edge course.
