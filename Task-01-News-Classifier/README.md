# News Topic Classifier Using BERT

## Overview
This project fine-tunes a **DistilBERT** model to classify news headlines into topic categories
using the **AG News dataset**.

## Model
- DistilBERT (Hugging Face Transformers)
- Fine-tuned for multi-class text classification

## Dataset
- AG News Dataset

## Demo (Local)
The application was tested locally using **Gradio**.

Local demo runs at:
http://127.0.0.1:7860

> Note: This is a local development link. A temporary public link was generated when running the app in Google Colab.

## Results
- Accuracy and F1-score evaluated on validation data
- Interactive predictions via Gradio UI
{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "source": [
        "\n",
        "# News Topic Classifier Using BERT\n",
        "\n",
        "## Overview\n",
        "This project is part of the **AI/ML Engineering Advanced Internship at DevelopersHub Corporation**.  \n",
        "It demonstrates how to **fine-tune a transformer model (DistilBERT)** to classify news headlines into topic categories using the **AG News dataset**.\n",
        "\n",
        "The notebook includes:  \n",
        "- Tokenization and preprocessing of the dataset  \n",
        "- Fine-tuning a transformer model  \n",
        "- Evaluation using **accuracy** and **F1-score**  \n",
        "- Live deployment using **Gradio** for interactive predictions  \n",
        "\n",
        "---\n",
        "\n",
        "## Dataset\n",
        "- **AG News Dataset** (Available via Hugging Face Datasets)  \n",
        "- **Training set:** 120,000 samples  \n",
        "- **Test set:** 7,600 samples  \n",
        "- **Classes:**  \n",
        "  1. World  \n",
        "  2. Sports  \n",
        "  3. Business  \n",
        "  4. Science/Technology  \n",
        "\n",
        "---\n",
        "\n",
        "## Technologies & Tools Used\n",
        "- Python 3  \n",
        "- Hugging Face Transformers  \n",
        "- Datasets library  \n",
        "- PyTorch  \n",
        "- scikit-learn  \n",
        "- Gradio  \n",
        "\n",
        "---\n",
        "\n",
        "\n"
      ],
      "metadata": {
        "id": "zVyAUPCpPE_M"
      }
    }
  ]
}
