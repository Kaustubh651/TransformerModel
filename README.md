
# GPT-like Language Model Training

This repository contains code for training a language model based on the GPT (Generative Pre-trained Transformer) architecture using PyTorch. The model is trained on a dataset, in this case, the "Wizard of Oz" text file, to generate text sequences.

## Contents

- `train_language_model.py`: Python script for training the language model.
- `wizard_of_oz.txt`: Text file used for training the language model.
- `requirements.txt`: File containing necessary Python dependencies.

## Getting Started

### Prerequisites

- Python 3.x
- PyTorch

### Installation

1. Clone this repository to your local machine.

```bash
git clone https://github.com/[USERNAME]/[REPOSITORY_NAME].git
```

2. Install the required Python packages.

```bash
pip install -r requirements.txt
```

### Usage

1. Run the `train_language_model.py` script to start training the language model.

```bash
python train_language_model.py
```

2. The script will load the "Wizard of Oz" text file and begin training the model. Adjust hyperparameters or dataset as needed.

3. Once training is complete, the model will generate text based on the provided prompt.

### Notes

- The `train_language_model.py` script includes adjustable parameters such as batch size, learning rate, and the number of training iterations.
- The code utilizes PyTorch's functionalities for building a GPT-like language model architecture.
