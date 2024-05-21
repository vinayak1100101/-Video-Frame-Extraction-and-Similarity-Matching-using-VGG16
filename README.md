# -Video-Frame-Extraction-and-Similarity-Matching-using-VGG16
This repository contains a Python script designed to extract frames from videos and find the most similar frame to a given query image using a pre-trained VGG16 model. The script is particularly useful for tasks involving video analysis and image similarity detection.

Features:

Frame Extraction: Extracts frames from video files at a specified interval.
Directory Traversal: Lists all video files in a specified directory.
Feature Extraction: Uses VGG16 pre-trained on ImageNet to extract features from frames and a query image.
Similarity Matching: Finds the frame most similar to the query image using cosine similarity.
Display Best Match: Optionally displays the best matching frame.


Dependencies:

OpenCV
TensorFlow
NumPy
Scikit-learn
Google Colab (for displaying images)


Notes
Adjust the interval parameter in extract_frames function to change the frequency of frame extraction.
Modify the file extensions in list_files_in_directory to include other video formats if needed.
Ensure the query image path is correct to avoid loading errors.  
