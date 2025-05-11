# Sentiment Analysis with Custom Text Classifier

This repository contains an end-to-end sentiment analysis pipeline using custom deep learning models implemented in PyTorch. It includes training, validation, inference, and visualization of performance metrics for text classification.

## Project Description

The notebook demonstrates a custom sentiment classifier trained on preprocessed text data using deep learning. It compares multiple model configurations and evaluates them using accuracy and loss metrics. The training loop, validation, and inference routines are implemented from scratch with visualization and interpretability.

## Key Features

- Tokenization and Padding with Preprocessing Utilities
- LSTM Models with different configirations 
- Training Loop with Real-time Loss & Accuracy Tracking
- Inference Loop with Sample Predictions

##  Dataset

The dataset used is a sentiment-labeled dataset IMDB. Each sample consists of a piece of text (such as a sentence or review) and its corresponding sentiment label.


## Models Compared

Three different model configurations were trained and compared based on:

- **Training Accuracy**
- **Training Loss**
- **Inference Results**

Each model's performance is visualized using line plots for comparison.

## Usage

### 1. Install Dependencies

```bash
pip install datasets torch matplotlib tqdm
```

### 2. Run the Notebook

Launch the notebook in a Jupyter environment:

```bash
jupyter notebook sent-analysis.ipynb
```

### 3. Results

- Visualizations of training losses and accuracies
- Printed inference samples with predictions vs ground truth
- Final validation accuracy

## 📊 Example Inference Output

```text
[Example 1]
Prediction: Negative
Ground Truth: Negative
----------------------------------------
[Example 2]
Prediction: Negative
Ground Truth: Negative
----------------------------------------
[Example 3]
Prediction: Negative
Ground Truth: Negative
----------------------------------------
 Inference Accuracy: 87.50%
```

## 📈 Training and Evaluation Plots

> Plots include:
> - Loss curves per epoch
> - Accuracy curves per epoch

![result](https://github.com/HeshamEL-Shreif/Sentiment-Analysis-with-LSTM/blob/main/output.png)


## 🧑‍💻 Author

- Hesham El-Shreif  
- GitHub: [@HeshamEL-Shreif](https://github.com/HeshamEL-Shreif)
