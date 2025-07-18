# 🖼️ Image Caption Generator
A deep learning project that generates human-like captions for images using a combination of CNN and RNN architectures.
## Overview
The Image Caption Generator is a deep learning model that takes an image as input and outputs a descriptive caption in natural language. It combines the power of Convolutional Neural Networks (CNNs) for image feature extraction and Recurrent Neural Networks (RNNs) (specifically LSTM) for sequence generation.
## Features
- 🔍 Extracts high-level visual features using VGG16
- 🧠 Generates captions using LSTM-based decoder
- 🗃️ Dataset support: Flickr8k
- ✅ Training, validation, and testing pipelines included
- 🌐 Easy deployment using Streamlit or Flask
## Model Architecture
```
Image → CNN Encoder → Feature Vector → LSTM Decoder → Generated Caption

```
## Installation
```
git clone https://github.com/Nguyenthanhduy16/SIC-2025.git
pip install -r requirements.txt

```
## Project Structure
```
Image_Caption_Generator/
│
├── data/                 # Dataset and preprocessing scripts
├── models/               # Model architecture and training code
├── app.py                # Streamlit Web App
├── image-captioner.ipynb     # Training 
├── requirements.txt
└── README.md

```
## Demo
Link: [HuggingFace](https://huggingface.co/spaces/newbieai05/Image_Caption_Generator)

