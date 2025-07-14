# Campus Compass: AI-Powered Real-Time Parking and Navigation
Campus Compass is a smart campus parking solution that uses deep learning and geospatial analysis to guide users to the nearest available parking space in real time. Developed as part of Clark University’s initiative to improve campus mobility, the system leverages a fine-tuned VGG19 model and Haversine-based routing to optimize user experience and reduce time spent searching for parking.

## Features
- Real-time detection of parking occupancy using PyTorch (VGG19)
- Input video feeds or images to detect vacant vs. occupied slots
- Distance-aware routing using Haversine formula
- Smart path suggestion from current location to closest available parking and destination building
- Poster presentation for IEEE ClarkHack MDC 2025
- Sample visual outputs with bounding boxes for classification

## Repository Structure
- `Classifier.ipynb`: Full code implementation for training, evaluation, and prediction
- `A.zip`: Dataset used to train the model (CNR Parking Dataset)
- `B.zip`: Dataset used for testing model generalizability
- `Campus_Compass_Poster.pptx`: Presentation poster summarizing the project
- `side_final_output.mp4`, `top_final_output.mp4`: Sample outputs showing real-time predictions

## Status
This project is currently under review for full deployment across Clark University's campus infrastructure.

## Future Work
- Indoor navigation support for building interiors
- Mobile app integration with live campus feeds
- Enhanced accessibility features for differently-abled students
