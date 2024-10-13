# Image Caption Generator

This project utilizes a Convolutional Neural Network (VGG16) in combination with a Long Short-Term Memory (LSTM) network to automatically generate captions for images. Additionally, the generated captions are transformed into audio using a text-to-speech module.

## Overview

The Image Caption Generator harnesses advanced deep learning techniques to interpret an image and produce a relevant descriptive caption. The model's architecture consists of:
- **VGG16**: A pre-trained convolutional neural network used for extracting image features.
- **LSTM**: A recurrent neural network that generates text sequences, such as captions.
- **Text-to-Speech**: Converts the generated text into audio form.

## Features

- Upload images directly through a web interface.
- Automatically generate captions for the uploaded images.
- Convert captions into audio for playback.
- Streamlit-based interface for a seamless user experience.

## How to Use

1. **Run the Streamlit application:**
   - Open your browser and navigate to the local Streamlit app URL (typically `http://localhost:8501`).
   - Upload an image using the file uploader.
   - The app will generate a caption for the image and provide an option to play the audio version of the caption.

2. **Try the app online:**
   You can try out the app directly by visiting [this link](https://image-caption-generator-19.streamlit.app).

## File Details

- `app.py`: Main script that runs the Streamlit application.
- `caption_generator.py`: Contains the logic for generating image captions using VGG16 and LSTM.
- `text_to_speech.py`: Handles the conversion of text captions into speech.
- `features.pkl`: Stores serialized features for the model.
- `model1.h5`: Pre-trained model file used for caption generation.
- `token.pkl`: Tokenizer file used for text processing.

## Dataset
The dataset used for training and evaluation of this model can be found [here](https://www.kaggle.com/datasets/srbhshinde/flickr8k-sau).

## Contributing

Contributions are encouraged! Feel free to fork the repository and submit a pull request with your improvements.

## Acknowledgements

- **VGG16**: For image feature extraction.
- **Streamlit**: For providing the web application framework.
- **TensorFlow and Keras**: For the deep learning libraries used to build and train the models.

---

Explore, experiment, and contribute to the project. Happy coding!

