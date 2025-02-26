# Real-Time-Language-Translation-Using-Neural-Machine-Translation

Overview
This project implements a real-time language translation system using Neural Machine Translation (NMT). The model leverages deep learning techniques to translate text or speech from one language to another with high accuracy. This implementation includes a graphical user interface (GUI) built using Tkinter.

Features
Real-time text translation

Image-based text extraction and translation using OCR

Support for multiple languages

Speech-to-text and text-to-speech integration

User-friendly interface

Scalable and efficient deep learning model

Technologies Used
Python

TensorFlow / PyTorch (for NMT model)

EasyOCR (for extracting text from images)

Google Translate API (as a backup translation service)

Tkinter (for GUI development)

Threading (for efficient translation processing)

Installation
Clone the repository:


cd real-time-translation
Install dependencies:

pip install -r requirements.txt
Run the application:

python app.py
Usage
Run the application and input text or speech in the source language.

The model translates the input in real-time and provides the output in the target language.

If speech is used, the translated text can be converted back into speech output.

Upload an image with text, and the OCR model will extract and translate the content.

Model Training
To train the NMT model from scratch:

python train.py --data data/dataset.csv --epochs 10 --batch_size 64
API Endpoints
POST /translate - Accepts text input and returns translated text.

POST /speech-to-text - Converts speech input into text.

POST /image-to-text - Extracts text from an image and translates it.

GET /supported-languages - Lists supported languages.

Future Enhancements
Improve model accuracy using transformer-based architectures.

Support for offline translation.

Enhance OCR accuracy with better preprocessing.

Mobile and web application integration.

Contributing
Contributions are welcome! Please submit a pull request or raise an issue if you find any bugs.
