Face Recognition System for Missing Persons

An AI-based Missing Person Detection System that uses facial recognition to identify individuals in CCTV footage. 
Users can upload an image of a missing person, which is analyzed using the MTCNN model for face detection and CNN-based feature extraction for recognition. The uploaded CCTV video is processed frame by frame to detect and compare faces with the input image using similarity metrics like cosine similarity.
The system highlights timestamps where a match is found and provides a tracked video for review. It also improves continuously as more data is processed, enhancing recognition accuracy over time. 

Features :

MTCNN-based Face Detection: Accurate face alignment and detection using pretrained Multi-task Cascaded CNN

Embedding Generation: 512-dimensional face embeddings for recognition

Web Interface: A React + Typescript based UI for image uploads and result visualization

REST API: FlaskAPI backend for processing requests
