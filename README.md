# Naruto Hand Sign Detection Model

## Introduction
This project aims to detect hand signs from the world-famous anime Naruto using machine learning techniques. The model is trained to recognize specific hand signs commonly seen in the anime.

## Methodology
The following steps were followed to create the hand sign detection model:

1. Hand detection: OpenCV (Open Source Computer Vision Library) was used to detect hands and track their movement in real-time.

2. Image preprocessing: Unwanted areas were cropped from the detected hand region to improve the accuracy of hand sign detection.

3. Dataset: A dataset containing images of the desired hand signs was obtained from Kaggle. This dataset was used to train the model.

4. Model training: The model was trained using the "Teachable Machine" platform, which provides a user-friendly interface for training machine learning models.

5. Model deployment: The trained model was deployed on the algorithm created earlier, integrating it with the hand detection algorithm. 

6. Prediction: The cvzone classification module was utilized to obtain predictions based on the deployed model.

## Usage
To use the Naruto Hand Sign Detection model, follow these steps:

1. Install the necessary dependencies mentioned in the requirements.txt file.

2. Run the algorithm that performs hand detection using OpenCV.

3. Once the hands are detected, the algorithm will crop the hand region and pass it through the trained model.

4. The cvzone classification module will generate predictions based on the hand sign detected.

5. The predicted hand sign can be used for various purposes, such as controlling virtual characters or triggering specific actions.

## Future Improvements
- Expand the dataset to include a wider range of hand signs from Naruto to improve the model's accuracy.
- Experiment with different machine learning algorithms and techniques to enhance the model's performance.
- Explore real-time video streaming for hand sign detection, allowing users to interact with the model through live video input.

## Acknowledgments
- Kaggle for providing the dataset used for training the model.
- OpenCV and cvzone for their contributions to computer vision and classification algorithms.
- The creators of the "Teachable Machine" platform for simplifying the process of training machine learning models.

## References
[1] OpenCV: https://opencv.org/

[2] Kaggle: https://www.kaggle.com/

[3] Teachable Machine: https://teachablemachine.withgoogle.com/

[4] cvzone: https://github.com/cvzone/cvzone
