# Text Translation and Text-to-Speech Synthesis

This project provides a pipeline to translate text to a chosen language using Google Translate, and then convert the translated text to speech using Tortoise-TTS.

## Table of Contents
1. [Features](#features)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Supported Languages](#supported-languages)
6. [License](#license)

## Features
- **Translation**: Translate text to a 5 different languages using Google Translate.The languages are 1). Arabic, 2). Urdu , 3). Japanese. 4). Korean, 5). Chinese. It basically asks users to add text that they want to add to add then it asks the users to select from above mentioned languages. Once the language is confirmed it translates it to and displays the translated text along with the audio for it.
- **Text-to-Speech**: Convert the translated text to speech using Tortoise-TTS.

## Requirements
- Python 3.7 to 3.10
- `pip` package manager

## Installation
Follow these steps to set up the project:

1. **Clone the Repository**
    ```sh
   !git clone https://github.com/152334H/tortoise-tts-fast
    !pip install git+https://github.com/openai/whisper.git
    !sudo apt update && sudo apt install ffmpeg
    !pip install transformers==4.29.2
    %cd tortoise-tts-fast
    !pip3 install -r requirements.txt --no-deps
    !pip3 install -e .
    !pip3 install git+https://github.com/152334H/BigVGAN.git
    ```
2. **Install these Libraries**
   ```sh
   !pip install googletrans==4.0.0-rc1
   !pip install whisper
   !pip install ipython
   !pip install torch torchaudio
   !pip install git+https://github.com/neonbjb/tortoise-tts.git
   ```


## Usage
To run the script, open a google colab or any Python environment and use the code given in file:
