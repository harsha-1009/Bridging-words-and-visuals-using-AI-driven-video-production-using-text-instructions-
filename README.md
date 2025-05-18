# Bridging-words-and-visuals-using-AI-driven-video-production-using-text-instructions-

Video Generation from Image and Text

This project demonstrates how to generate a short video using an input image and a text prompt by leveraging a simplified multimodal pipeline.

Steps to Execute

1. Download and Upload Dataset

Download the MSR-VTT dataset from https://www.kaggle.com/datasets/vishnutheepb/msrvtt

Upload the downloaded dataset to your Google Drive.

2. Prepare the Dataset

Open the notebook DatasetPreparation.ipynb in Google Colab.

Run the notebook to set up the dataset properly inside your Google Drive.

3. Upload Image Input

Upload your input image into the msr-vtt folder in your Google Drive.

4. Generate Video

Open the VideoGenUsingImageText.ipynb notebook in Google Colab.

Connect to a high-performance GPU (preferably A100).

Modify the text prompt in the notebook to match the description of the uploaded image.

Run the notebook to generate the video.

5. Access the Output

The generated video will be saved in your Google Drive as generated_video.mp4.
