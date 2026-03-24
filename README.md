🎙️ DeepFake Voice Detection using CNN–LSTM
🧠 Project Overview

This project aims to detect AI-generated (DeepFake) voices from real human voices using a hybrid Deep Learning model that combines Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) layers. The model analyzes Mel-Frequency Cepstral Coefficients (MFCC) features extracted from audio signals to classify whether the voice is real or fake.

🚀 Key Features

🔍 Detects DeepFake (synthetic) vs Human (real) voices.

🎧 Accepts .wav audio files or real-time microphone recordings as input.

⚙️ Uses MFCC feature extraction for robust speech representation.

🧩 Combines CNN (for spatial feature extraction) and LSTM (for temporal sequence learning).

📉 Achieves a training loss as low as 0.0003, showing strong convergence.

📊 Generates accuracy, confusion matrix, and F1-score metrics.

🧬 Model Architecture

Preprocessing

Audio normalization

MFCC extraction (40 coefficients)

Padding/truncating to uniform length

Model Layers

CNN layers for spatial feature extraction

LSTM layers for sequence learning

Dense layers for final classification

Output:

Binary classification → 0 = Fake voice, 1 = Human voice

🧩 Tech Stack

Language: Python

Libraries: TensorFlow / Keras, Librosa, NumPy, Scikit-learn, Matplotlib

Environment: Jupyter Notebook / VS Code

🧠 Training Details

Dataset: Custom dataset of human and AI-generated voices

Optimizer: Adam

Loss Function: Binary Crossentropy

Epochs: 50+

Final Training Loss: 0.0003

📈 Evaluation Metrics

Accuracy: ~99% on validation data

F1-Score: High precision and recall

Confusion Matrix: Shows strong differentiation between real and AI-generated voices

🗣️ Real-Time Testing

You can record an audio clip directly using a microphone and test whether it is AI-generated or human-generated.

Note: Model may need further tuning for real-world recordings due to background noise, codec differences, and microphone variations.

🔮 Future Improvements

Improve detection for low-quality or noisy recordings

Expand dataset with more AI voice types (e.g., cloned voices from various models)

Integrate a web or mobile app interface for live testing

Apply spectrogram augmentation for better generalization

📚 Research Insight

With the rise of AI voice cloning and DeepFake scams, this project demonstrates a practical deep learning-based approach to authenticate voice data and combat audio-based identity fraud.

🧑‍💻 Author

Selvasri K
B.Tech in Artificial Intelligence and Data Science
Karpaga Vinayaga College of Engineering and Technology
📍 Tamil Nadu, India
