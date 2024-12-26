# Fine-Tuning a Generative AI Model

## Description
This repository contains a Jupyter Notebook titled **PEFT_Fine_Tuning.ipynb**, which provides a step-by-step guide to fine-tuning a generative AI model. The notebook explores techniques to adapt a pre-trained language model to specific tasks or datasets, enhancing its performance and applicability.

## Features
- Introduction to the challenges of evaluating LLMs.
- Comparison of traditional machine learning evaluation methods with those required for LLMs.
- Implementation of key evaluation metrics:
  - **ROUGE (Recall-Oriented Understudy for Gisting Evaluation)**
  - **BLEU (Bilingual Evaluation Understudy)**
- Demonstrates fine-tuning of generative models on custom datasets.
- Practical examples and calculations for metrics like ROUGE-1, ROUGE-2, and ROUGE-L.

## Prerequisites
To run the notebook, ensure you have the following installed:
- Python 3.8 or later
- Jupyter Notebook or JupyterLab
- Required Python libraries (install using the provided requirements file):
  - `transformers`
  - `datasets`
  - `torch`
  - `numpy`
  - `scipy`

## Prerequisites
1. Install Python 3.8 or higher.
2. Install the required Python packages using the provided `requirements.txt`.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/RuvenGuna94/LLM-Fine-Tuning.git
   cd LLM-Fine-Tuning
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the notebook `PEFT_Fine_Tuning.ipynb` in Jupyter Notebook or VS Code.
2. Follow the steps outlined in the notebook to fine-tune the FLAN-T5 model.
3. Evaluate the model's performance using the ROUGE metric.

## Contributing
Feel free to fork the repository and submit pull requests. Suggestions and improvements are welcome!

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Developer Log
### 24 December 2024
- Created the repo, directory and all necessary files
- Configured local env to run code
  - Installed required conda env and kernel

### 25 December 2024
- Updated all version libraries such that it is able to run
- Load and test base model with zero shot inference
- Fine tuning
  - Preprocessed dataset with instructional prompt
  - Create train, validation and test sets
  - Fine tune with minimum configs to reduce compute requirements
  - Evaluate against base model (Human evaluation and ROUGE metric)




