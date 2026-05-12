Voice Authenticity Detection using Machine Learning
Dataset Setup
1. Source: Download the DEEP-VOICE: DeepFake voice recognition dataset from Kaggle.
2. Placement: Upload the dataset folder (containing the REAL and FAKE subfolders) to your Google Drive.
3. Path: Ensure the data is located at /content/drive/MyDrive/ or update the drive.mount path in the first cell of the notebook to match your location.
Quick Start
1. Open the .ipynb file in Google Colab.
2. Run the Preprocessing cells to resample audio and apply the augmentation pipeline (Noise, Pitch Shift, Time Stretch) .
3. Execute the Training cells for the Enhanced CNN, GRU, or classical models.