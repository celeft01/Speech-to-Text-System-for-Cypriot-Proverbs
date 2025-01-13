Speech-to-Text System for Cypriot Proverbs

This repository hosts the implementation of a speech-to-text system designed to transcribe spoken Cypriot proverbs. The system is built by fine-tuning OpenAI's Whisper model and aims to contribute to the preservation of Cypriot cultural heritage.

Table of Contents

Introduction

Dataset

Project Overview

Usage

Results

Contributing

License

Introduction

Cypriot proverbs are a valuable part of the island's cultural heritage, reflecting the wisdom and traditions of its people. This project leverages advancements in AI to process and transcribe spoken Cypriot proverbs, ensuring their documentation and accessibility for future generations. By fine-tuning OpenAI's Whisper model, the system achieves high accuracy in understanding and transcribing the unique linguistic patterns of the Cypriot dialect.

Dataset

Source: Custom-recorded dataset of spoken Cypriot proverbs.

Size: Contains audio recordings of native speakers reciting a curated collection of Cypriot proverbs.

Format: WAV files with corresponding text transcriptions for training and evaluation.

Project Overview

Objectives

Fine-tune OpenAI's Whisper model for Cypriot dialect speech recognition.

Transcribe and process spoken Cypriot proverbs with high accuracy.

Preserve and document the linguistic heritage of Cyprus.

Workflow

Data Preparation:

Audio preprocessing: Noise reduction, segmentation, and alignment.

Text transcription alignment for supervised training.

Model Fine-Tuning:

Base Model: OpenAI Whisper

Fine-tuning on the curated Cypriot proverbs dataset.

Evaluation:

Metrics: Word Error Rate (WER), Character Error Rate (CER).

Comparison with baseline transcription models.

Deployment:

Export model for usage in transcription pipelines.

Create a user-friendly interface for interacting with the model.

Tools and Technologies

Programming Language: Python

Libraries: OpenAI Whisper, PyTorch, Librosa, NumPy, Pandas

Environment: Jupyter Notebook for experimentation and development.

Usage

Prerequisites

Python 3.8 or higher

Install dependencies using pip install -r requirements.txt.

Instructions

Clone the repository:

git clone https://github.com/your-username/Speech-to-Text-System-for-Cypriot-Proverbs.git

Navigate to the project directory:

cd Speech-to-Text-System-for-Cypriot-Proverbs

Open the Jupyter notebook:

jupyter notebook Project_DONE.ipynb

Follow the steps in the notebook to preprocess data, train the model, and test the system.

Results

The fine-tuned Whisper model achieved the following results:

Word Error Rate (WER): [Add WER value]

Character Error Rate (CER): [Add CER value]

Accurate transcription of Cypriot proverbs, capturing dialectal nuances and phonetic variations.

Detailed results and visualizations are included in the notebook.

Contributing

Contributions to this project are welcome! If you wish to add features, improve performance, or expand the dataset, please follow these steps:

Fork the repository.

Create a new branch:

git checkout -b feature-branch

Commit your changes:

git commit -m 'Add new feature or improvement'

Push to the branch:

git push origin feature-branch

Open a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements

OpenAI for providing the Whisper model.

Contributors to the development of open-source libraries used in this project.

Native Cypriot speakers who provided the audio data for training.
