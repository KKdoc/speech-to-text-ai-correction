Speech-to-Text with AI Correction System
This repository contains the core Python code for a Speech-to-Text transcription system utilizing OpenAI Whisper. The system processes audio files and evaluates transcription quality using publicly available datasets.

Features
	•	High-quality transcription using Whisper by OpenAI.
	•	Performance evaluation with Word Error Rate (WER) and Character Error Rate (CER).
	•	Modular and adaptable code for various use cases.
	•	Compatible with publicly available datasets for training and testing.

Dataset
The project uses the Mozilla Common Voice Dataset, which is a publicly available dataset for training speech-to-text models. Details about the dataset:
	•	Dataset Name: Mozilla Common Voice
	•	Version: cv-corpus-20.0-delta-2024
	•	Language: English
	•	Processed Files: validated.tsv
	•	Source: Common Voice by Mozilla
This dataset was chosen for its diversity in accents, age groups, and speaking styles, ensuring robust performance across various real-world scenarios.

Code Overview
The repository includes:
	•	Transcription Script: Processes audio files from the dataset and generates transcriptions.
	•	Evaluation Script: Calculates WER and CER for assessing transcription quality.

How to Use
	1	Download the Dataset:
	◦	Obtain the dataset from the Common Voice website.
	◦	Extract the dataset and place it in your preferred directory.
	2	Install Dependencies:
	◦	Install the required libraries manually:
	▪	Whisper by OpenAI
	▪	Pandas
	▪	JiWER
	▪	Librosa
	▪	PyTorch
	3	Run the Code:
	◦	Use the transcription script to generate text outputs from audio files.
	◦	Use the evaluation script to calculate WER and CER metrics.

Dependencies
The following Python libraries are required:
	•	Whisper by OpenAI
	•	Pandas
	•	JiWER
	•	Librosa
	•	PyTorch
Please ensure these libraries are installed before running the code.

Results
The project achieved the following performance metrics:
	•	Validation WER: 23.2%
	•	Validation CER: 9.2%
	•	Test WER: 13.5%
	•	Test CER: 4.6%
These results demonstrate high transcription quality with minimal errors.

License
This project is licensed under the MIT License, allowing free use, modification, and distribution.

Acknowledgments
Special thanks to:
	•	OpenAI for the Whisper transcription model.
	•	Mozilla for providing the Common Voice dataset.
	•	Contributors of Python libraries like Pandas, Librosa, JiWER, and PyTorch.
