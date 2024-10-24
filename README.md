# Hand Gesture Sign Detector

## Overview

This project aims to develop a Hand Gesture Sign Detector using YOLOv11 for real-time recognition of specific hand gestures. The model is trained to detect five distinct signs: "Hello," "I Love You," "Yes," "No," and "Thanks." The goal is to create an accessible tool for translating hand gestures into text, enhancing communication for the hearing impaired and facilitating human-computer interaction.

## Project Structure

### Data Collection

- **Dataset Creation:** A dataset was compiled containing images of the target hand gestures, ensuring diversity in hand positioning, backgrounds, and lighting conditions.

### Model Development

#### YOLOv11 Implementation

- **Model Architecture:** The YOLOv11 architecture was utilized for its high efficiency in real-time object detection.
- **Training:** The model was trained on the prepared dataset, with specific attention to tuning hyperparameters for optimal performance.

### Gesture Recognition Pipelines

- **Real-Time Detection Pipeline:** A streamlined pipeline was created to handle video input from the webcam, process frames, and output detected gestures in real-time.
- **Post-Processing:** Confidence thresholds were set to filter out low-confidence predictions, ensuring accuracy in gesture recognition.

## Results and Conclusion

After extensive testing and validation, the YOLOv11 model achieved high accuracy in recognizing the specified gestures. The real-time detection capability demonstrated promising results, making it a practical tool for enhancing communication through sign language. The project highlights the effectiveness of modern deep learning techniques in gesture recognition, paving the way for further advancements in accessibility and human-computer interaction technologies. 

Overall, the Hand Gesture Sign Detector successfully bridges the gap between visual communication and digital interfaces, showcasing the potential of machine learning in everyday applications.
