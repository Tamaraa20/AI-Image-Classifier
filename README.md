# AI Image Classifier

This is a simple web app that uses a pre-trained MobileNetV2 model to classify images. Upload an image and let AI tell you what is in it!

Built with Streamlit and powered by TensorFlow, this app uses MobileNetV2 trained on ImageNet to return the top 3 predictions with confidence scores.

## Features

- Upload images in JPG, JPEG, or PNG format
- Classifies images using MobileNetV2 (trained on ImageNet)
- Displays top 3 predictions with confidence scores
- Easy-to-use Streamlit interface

## Requirements

- Python 3.7+
- streamlit
- tensorflow
- pillow
- opencv-python

## Installation

1. Clone this repository:
    ```sh
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. Install dependencies:
    ```sh
    pip install streamlit tensorflow pillow opencv-python
    ```

## Usage

Run the app with:

```sh
streamlit run main.py
```

Then open the provided local URL in your browser.
<img width="1030" height="416" alt="image" src="https://github.com/user-attachments/assets/72c3c643-1c88-4960-9a7f-643eea5e670a" />

<img width="830" height="783" alt="image" src="https://github.com/user-attachments/assets/166f2771-a749-4701-8e15-e270a6683ac2" />


