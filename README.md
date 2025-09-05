# VUI Speech Recognizer

**Building a Deep Neural Network as Part of an End-to-End Automatic Speech Recognition (ASR) Pipeline**

This project focuses on developing a deep neural network for automatic speech recognition (ASR). The pipeline begins by converting raw audio into feature representations commonly used in ASR and progresses to mapping these features to transcribed text.

---

## Project Overview

- **`Dataset`**: Utilizes the LibriSpeech dataset, a corpus of read English speech.
- **`Preprocessing`**: Converts raw audio files into feature representations suitable for training.
- **`Model`**: Implements a deep neural network to map audio features to text.
- **`Objective`**: Build an end-to-end ASR system capable of transcribing spoken language into written text.

---

## Repository Structure

- **`vui_notebook.ipynb`** — Jupyter notebook containing the complete workflow for building and training the ASR model.
- **`train_utils.py`** — Utility functions for training the model.
- **`data_generator.py`** — Script for loading and preprocessing the dataset.
- **`char_map.py`** — Maps characters to indices and vice versa.
- **`utils.py`** — General utility functions.
- **`train_corpus.json`** — Training corpus data.
- **`valid_corpus.json`** — Validation corpus data.
- **`sample_models.py`** — Defines sample model architectures.
- **`requirements.txt`** — List of required Python packages.
- **`README.md`** — This file.

---

## Running the Notebook

1. Clone the repository:

    `git clone https://github.com/hamidghasemi69/VUI-Speech-Recognizer.git`
    
    `cd VUI-Speech-Recognizer`

2. Open the Jupyter notebook:

  `jupyter notebook vui_notebook.ipynb`

3. Follow the instructions in the notebook to preprocess the data, define the model, train it, and evaluate its performance.

---

## Results

The model demonstrates the ability to transcribe spoken language into written text, achieving satisfactory accuracy on the validation set.

<img width="689" alt="asr" src="https://github.com/hamidghasemi69/VUI-Speech-Recognizer/assets/22797186/7fcf8672-1b9a-4f7a-976e-350d3b34c7dc">


---

## Acknowledgements

- `LibriSpeech Dataset`: A corpus of read English speech used for training and evaluating the ASR model.

- `PyTorch`: An open-source machine learning library used for building and training the deep neural network.


---

## Contact & Contributions

- Author: `Hamid Ghasemi`

- Contributions are welcome! Please submit a pull request or raise an issue if you find a bug or have suggestions for improvement.


