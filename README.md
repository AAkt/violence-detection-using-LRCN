# violence-detection-using-LRCN
Violence detection model is just another model which can detect violence in videos using an open dataset present on kaggle of 2000 videos.

The code defines a Long Short-Term Memory with Convolutional Neural Network (LRCN) model for video classification. The unique feature is the combination of convolutional layers (Conv2D) with Long Short-Term Memory (LSTM) layers. This architecture is particularly effective for recognizing temporal patterns in video sequences. The TimeDistributed layer is used to apply operations such as convolution and pooling across the temporal dimension. The model aims to capture both spatial features through convolution and temporal dependencies through LSTM, making it suitable for tasks like action recognition in videos.

The link for dataset:-https://www.kaggle.com/datasets/mohamedmustafa/real-life-violence-situations-dataset

Violence detection models are used in social media, video surveillance, and online platforms to automatically identify and mitigate violent or harmful content, ensuring user safety and ethical standards. Applications include content moderation, security enhancement, and support for law enforcement and humanitarian efforts.


