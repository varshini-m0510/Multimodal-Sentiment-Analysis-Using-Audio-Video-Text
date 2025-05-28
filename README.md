# Multimodal-Sentiment-Analysis-Using-Audio-Video-Text

🔍 Overview:
Developed a deep learning pipeline for multimodal sentiment analysis by combining text, audio, and video features from dialogue-based data. This project processes input videos to extract sentiment representations using state-of-the-art models and libraries, and classifies the sentiment using a unified multimodal neural network.

Tech Stack: Python, PyTorch, BERT, ResNet, Librosa, OpenCV, Transformers, Pandas

🧩 Features:
🔤 Text Embeddings: Utilized BERT to generate contextual sentence embeddings.

🎙️ Audio Features: Extracted MFCC features using librosa for emotion recognition.

🎥 Video Features: Leveraged ResNet-50 and OpenCV to compute visual cues.

🤖 Multimodal Fusion: Combined all three modalities and trained a PyTorch-based neural network for sentiment classification.

📊 Result: Achieved classification into positive, neutral, or negative sentiment labels with fully automated data preprocessing and inference pipeline.

📦 Output:
Trained model

Prediction file (Submission.csv)

Modular and reproducible code for each processing stage
