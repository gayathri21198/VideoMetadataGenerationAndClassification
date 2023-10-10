# VideoMetadataGenerationAndClassification
This project is done as a part of final year of Masters program

## Problem Statement
This project aims to address the following problem at hand which involves the categorization of video documentaries related to various ISRO missions and programs. The existing collection of video programs requires extensive metadata generation and verification in order to facilitate effective organization and retrieval. By developing an automated system that can analyze objects, text, speech, and named entities to classify the videos into distinct genres. These genres include launch programs, interviews, educational programs, outdoor shots, public shots, traffic, and more. By leveraging deep learning methods, the system should be capable of understanding the visual and textual content of the videos to accurately assign appropriate genre labels.

## Objective
The objective of this project is to develop a comprehensive system for object recognition in videosusing the YOLO (You Only Look Once) algorithm and text extraction from videos using Optical Character Recognition (OCR) techniques. The system aims to extract both detected objects and extracted text as features and utilize them to train a multi-class classification model for video classification.

## Steps
1. Train YoloV7 model on a custom dataset for real-time Object detection
2. Extract the text features using the OCR text extraction techniques
3. Extract the audio transcript from the speech in the video using Speech Recognition techniques
4. With these feature extraction - a labeled dataset is created and used for training a multi-class classification model
5. Explored feature extractors like MobileNet, ResNet-50 and InceptionV3 with the LSTM models for video classification 
