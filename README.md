

## CNN-HAND-WRITTEN-DIGIT-RECOGNITION-ML

**Overview:**
This project leverages Convolutional Neural Networks (CNNs) to perform handwritten digit recognition. Utilizing the MNIST dataset, the project extends its capabilities to recognize digits created in paint applications and within video frames. The application demonstrates a flexible and comprehensive approach to digit recognition across various inputs.

**Features:**

- **MNIST Dataset Recognition:** Accurately identifies handwritten digits (0-9) from the MNIST dataset using a trained CNN model.
- **Paint Application Detection:** Recognizes handwritten digits created in paint applications, allowing for broader application beyond the MNIST dataset.
- **Video Image Recognition:** Employs computer vision techniques to extract frames from video streams and applies digit recognition to identify digits within these frames, enabling real-time recognition from video input.

**Technologies Used:**

- **Python:** Programming language used for implementing the machine learning model and image processing.
- **Convolutional Neural Networks (CNNs):** Deep learning architecture for recognizing patterns in handwritten digits.
- **OpenCV:** Library used for video processing and frame extraction.
- **TensorFlow or PyTorch:** Frameworks for building and training the CNN model.
- **MNIST Dataset:** A dataset of handwritten digits used for training and evaluating the model.

**Usage:**

1. **Training the Model:**
   - Train the CNN model using the MNIST dataset to build a model capable of recognizing handwritten digits.
   - Follow the provided scripts to preprocess the dataset, train the model, and evaluate its performance.

2. **Paint Application Integration:**
   - Implement functionality to recognize handwritten digits from images created in paint applications.
   - Adjust the model and preprocessing steps to handle variations in digit appearance and background.

3. **Video Processing:**
   - Use OpenCV to capture and process video frames.
   - Apply the trained CNN model to each frame to detect and recognize handwritten digits in real-time.

**Getting Started:**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/CNN-HAND-WRITTEN-DIGIT-RECOGNITION-ML.git
   ```

2. **Install Dependencies:**
   - Install required Python libraries:
     ```bash
     pip install -r requirements.txt
     ```

3. **Train the Model:**
   - Run the training script provided in the repository to train the CNN model:
     ```bash
     python train_model.py
     ```

4. **Detect Digits in Paint Applications:**
   - Follow the instructions in `paint_detection.py` to set up detection for paint application images.

5. **Video Frame Recognition:**
   - Use `video_recognition.py` to process video frames and perform digit recognition.

