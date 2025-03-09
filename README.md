# Burmese_Speech_to_Text

This repository contains a Jupyter Notebook for fine-tuning OpenAI's Whisper model on Burmese audio data for speech recognition. The notebook loads a dataset and provides a framework for processing and improving Whisper's performance on Burmese speech.

### Project Description

OpenAI Whisper is a powerful speech recognition model capable of transcribing audio into text. This notebook provides a structured approach to fine-tuning Whisper with Burmese audio data to improve its accuracy for the Burmese language.

### Why Use This Project?

- Fine-tunes OpenAI's Whisper model for better performance on Burmese speech.

- Provides a step-by-step Jupyter Notebook for easy implementation.

- Uses a public dataset specifically for Burmese speech recognition.

### Usage

1. Clone the repository and open the notebook.

2. Install the required dependencies.

3. Run the cells to load the dataset and process it with Whisper.

### Dataset

The notebook uses a Burmese speech dataset available on Hugging Face:
``` 
from datasets import load_dataset

ds = load_dataset("YeBhoneLin10/openai-whisper-SLR")
```

### Fine-Tuning Process

The fine-tuning process involves:

1. Loading the dataset – Burmese speech audio and transcriptions.

2. Preprocessing the data – Converting audio files into the appropriate format.

3. Training the model – Fine-tuning Whisper on the Burmese dataset.

4. Evaluating performance – Measuring accuracy and making improvements.

### License

This project is released under an open-source license. Please check the dataset's terms of use before utilizing it in commercial applications.
