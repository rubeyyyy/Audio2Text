# Audio2Text

This notebook demonstrates the use of the Whisper automatic speech recognition model from OpenAI. It covers various aspects of the model, including installation, importing required packages, loading the model, and performing speech recognition tasks. Additionally, it explores features like translation and timestamp generation, as well as distillation and the use of flash attention for improved performance.
Prerequisites
Before running the notebook, ensure you have the following dependencies installed:

Python
PyTorch
Transformers
Accelerate
Datasets
Flash-attn (optional)
Optimum (optional)

You can install the required packages using the following commands:

```python
!pip install --q --upgrade pip
!pip install --q --upgrade git+https://github.com/huggingface/transformers.git accelerate datasets[audio]
!pip install --q flash-attn --no-build-isolation
!pip install --q optimum
```


Usage

Install the required packages.
Import the necessary packages.
Load the Whisper model and processor.
Create a pipeline for automatic speech recognition.
Provide the path to an audio file.
Run the pipeline on the audio file to obtain the transcribed text.
Explore additional features like translation, timestamp generation, distillation, and the use of flash attention.

Sections
The notebook is divided into the following sections:

Installation
Import required packages
Load the Whisper model
Create an automatic speech recognition pipeline
Perform speech recognition
Translation
Distill Whisper
Flash attention

Each section includes relevant code snippets and explanations.
Note: Make sure to replace 'path_to_your_audio' with the actual path to your audio file.
