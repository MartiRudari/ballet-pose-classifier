# Ballet Pose Classification Using LSTM and MediaPipe
This project presents an LSTM-based neural network for real-time classification of ballet poses, using MediaPipe for pose detection and a custom dataset of ballet movements. It was developed as part of my Bachelor's thesis research, combining technical interests with my background as a professional ballet dancer.

# Ballet Movements Classified
Demi-plié (first position)
Battement tendu (to the side)
Relevé (first position)
Attitude croisé
First arabesque
Retiré devant

# Technologies Used
Python
TensorFlow / Keras
MediaPipe Holistic
NumPy
Matplotlib / TensorBoard

# Model Architecture
3 LSTM layers + 2 dense layers
Softmax output over 6 classes
Trained over 4800 labelled pose frames
95:5 train-test split
Optimiser: Adam
Activation: ReLU, Softmax

# Performance
Trained for 2000 epochs
Pose added to the sequence only if the prediction >80% confidence
Real-time classification with high accuracy

# Folder Overview
/src/: Core functions and model
/data/: Pose data in .npy format
/models/: Saved trained model
/article/: Full PDF write-up of the project
/media/: Pose figures and architecture diagrams

# Full Report
You can find the full project article in /article/LSTM_RNN_for_ballet_sequences.pdf.

# Future Work
Integrate with a GAN to generate new ballet sequences
Add support for full choreography recognition
Use wearable sensors for higher precision
