# Speech-to-Text System for Cypriot Proverbs

This repository hosts the implementation of a speech-to-text system designed to transcribe spoken Cypriot proverbs. The system is built by fine-tuning OpenAI's Whisper model and aims to contribute to the preservation of Cypriot cultural heritage.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Project Overview](#project-overview)
4. [Results](#results)
5. [License](#license)

---

## Introduction

Cypriot proverbs are a valuable part of the island's cultural heritage, reflecting the wisdom and traditions of its people. This project leverages advancements in AI to process and transcribe spoken Cypriot proverbs, ensuring their documentation and accessibility for future generations. By fine-tuning OpenAI's Whisper model, the system achieves high accuracy in understanding and transcribing the unique linguistic patterns of the Cypriot dialect.

---

## Dataset

- **Source**: Custom-recorded dataset of spoken Cypriot proverbs.
- **Data Type**: Contains audio recordings of native speakers reciting a curated collection of Cypriot proverbs.
- **Format**: WAV files with corresponding text transcriptions for training and evaluation.

---

## Project Overview

### Objectives
1. Fine-tune OpenAI's Whisper model for Cypriot dialect speech recognition.
2. Transcribe and process spoken Cypriot proverbs with high accuracy.
3. Preserve and document the linguistic heritage of Cyprus.

### Workflow
1. **Data Preparation**:
   - Audio preprocessing: Noise reduction, segmentation, and alignment.
   - Text transcription alignment for supervised training.
2. **Model Fine-Tuning**:
   - Base Model: OpenAI Whisper
   - Fine-tuning on the curated Cypriot proverbs dataset.
3. **Evaluation**:
   - Metrics: Word Error Rate (WER).
   - Comparison with baseline transcription models.
   - Tested on many new recordings.
4. **Deployment**:
   - Export model for usage in transcription pipelines.
   - Create a user-friendly interface for interacting with the model.

### Tools and Technologies
- **Programming Language**: Python
- **Libraries**: OpenAI Whisper, PyTorch, Librosa, NumPy, Pandas
- **Environment**: Jupyter Notebook for experimentation and development.

---

## Results

The fine-tuned Whisper model achieved the following results:
- **Word Error Rate (WER)**: Can be seen in the notebook
- Accurate transcription of Cypriot proverbs, capturing dialectal nuances and phonetic variations.

Detailed results are included in the notebook.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgements

- OpenAI for providing the Whisper model.
- Contributors to the development of open-source libraries used in this project.
- Native Cypriot speakers who provided the audio data for training.
- Foivos Lympouras, Maria Erodotou, Andreas Papadopoulos

