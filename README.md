# Voice-to-Sign-Language Translator

Welcome to the Voice-to-Sign-Language Translator project! This innovative application translates spoken language into sign language using advanced machine learning models. Leveraging Google Teachable Machine and Python, this project aims to bridge communication gaps for the hearing-impaired community by converting spoken words into sign language gestures.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The Voice-to-Sign-Language Translator is a Python-based application that utilizes Google Teachable Machine models to translate user voice input into sign language. The project integrates various technologies to provide real-time conversion, enabling seamless communication.

Key components of the project include:

- **Voice Recognition:** Captures and processes spoken input using the SpeechRecognition library.
- **Machine Learning Models:** Utilizes pre-trained models from Google Teachable Machine to interpret spoken words and map them to corresponding sign language gestures.
- **Sign Language Display:** Uses OpenCV and tkinter to display sign language gestures on-screen.

## Features

- **Real-time Voice Recognition:** Converts spoken words into text using SpeechRecognition.
- **Customizable Machine Learning Models:** Integrates with Google Teachable Machine models for accurate sign language translation.
- **Sign Language Visualization:** Displays sign language gestures in real-time using OpenCV and tkinter.
- **User-Friendly Interface:** Easy-to-use graphical interface for interaction and visualization.

## Installation

To set up the Voice-to-Sign-Language Translator, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Inspirathon/Team-Akatsuki.git
   cd Team-Akatsuki
2. **Download the required pacakges:**
    ```bash
       pip install opencv-python-headless  cvzone numpy mediapipe tensorflow SpeechRecognition easygui Pillow pyaudio

3. **Download the System Dependecies:**
    ```bash
      sudo apt-get install portaudio19-dev
## Usage
  To run the main script or other components, use the following commands

  **Run the main script:**
   ```bash
      cd speechtosign
      chmod+ x run.sh
      ./run.sh


