# AcoustiTranscribe-AI-Powered-Speech-to-Text-System

## Project Overview
AcoustiTranscribe is a robust **Automatic Speech Recognition (ASR)** tool powered by **OpenAI's Whisper Model**. It swiftly converts spoken language into accurate text, ensuring seamless transcription across languages and noisy environments. Ideal for real-time applications, accessibility solutions, and voice-driven systems, it offers high-performance processing with minimal latency.

---

## Key Features
- High-Accuracy Transcription: Leverages OpenAI's Whisper pre-trained model for precise speech recognition.
- Multilingual Support: Processes audio in multiple languages, broadening its usability.
- Noise Robustness:Effectively handles noisy audio inputs to improve transcription quality.
- Real-Time Processing: Supports real-time audio input for instant transcription using PyAudio.
- Customizable Outputs: Allows integration with other systems for flexible output formats.

---

## Technology Stack
- Programming Language: Python 3
- Libraries and Frameworks:
  - OpenAI Whisper
  - PyAudio
  - NumPy
  - Pandas
  - Scikit-learn
  - Scipy
- Environment:Google Colab or Jupyter Notebook

---

## Setup and Installation

1. Clone the Repository:
```
git clone <repository_url>
```
2. Install Dependencies:
```
pip install -r requirements.txt
```
3. Run the Project:
Open the provided Jupyter Notebook file (`OpenAI_ASR_demo.ipynb`) in Google Colab or Jupyter Notebook.

---

## Usage Instructions
1. Load the Dataset:
   - Upload audio files for transcription.
2. Preprocess Audio Data:
   - Apply noise reduction if required.
3. Run the Model:
   - Execute the Whisper model for transcription.
4. Analyze Outputs:
   - Review, edit, and save the transcription results in text format.

---

## Evaluation Metrics
- Accuracy: Evaluates correctness of transcriptions.
- Word Error Rate (WER): Measures error rates in output.
- Latency: Tests real-time performance for live transcription.

---

## Applications
- Real-Time Speech Recognition: Meetings, conferences, and live captions.
- Accessibility Tools: Assisting hearing-impaired individuals.
- Voice Interfaces:Chatbots and virtual assistants.
- Language Translation Tools: Multilingual transcription for translation services.
