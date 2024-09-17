Entity Recognizer for Weights and Volumes
Overview
This project focuses on recognizing and extracting critical entity values related to weights, volumes, and maximum recommended weights from images. It utilizes the Google Cloud Vision API for text extraction and regular expression pattern matching to identify and categorize entities.

Features
Image Text Extraction: Extracts text from images using the Google Cloud Vision API.
Entity Recognition: Identifies weights, volumes, and maximum recommended weights from the extracted text.
Data Storage: Saves recognized entities to an SQLite database for further analysis.
Data Visualization: Generates histograms to visualize the distribution of extracted weights, volumes, and maximum weights.
Prerequisites
Google Cloud Vision API Key: Ensure you have a service account key in JSON format for authentication.

Python Libraries: Install the required Python libraries using pip.


pip install google-cloud-vision opencv-python Pillow transformers numpy==1.21.6 matplotlib==3.4.3
Setup
Google Cloud Vision API Configuration

Ensure you have the Google Cloud Vision API key in JSON format. Set up your Google Cloud project and enable the Vision API.

Prepare Your Environment

Install the necessary Python libraries as outlined in the prerequisites.
