# Computer Vision Course Assignment: Simpsons Character Classification

## Overview

Welcome to the Simpsons Character Classification Kaggle competition for the Computer Vision course! In this competition, your task is to build a model that accurately classifies images of Simpsons characters. The goal is to achieve the highest accuracy on the provided dataset.

### Getting Started

1. **Join the Kaggle Competition:**
  - Follow the competition link provided to join the Kaggle competition.
  - Familiarize yourself with the competition data and evaluation metric.

2. **Clone this repository to your local machine:**
     ```bash
     git clone https://github.com/mshamrai-teaching/image-classification-simpsons-*your-name*
     ```
3. **Navigate to the project directory:**
      ```bash
       cd image-classification-simpsons-*your-name*
      ```

### Guidelines

* Dataset:
  * The Simpsons character dataset is provided for this competition.
* Model:
  * Build a model for image classification to identify Simpsons characters.
  * Transfer learning is highly encouraged; you can use pre-trained models or fine-tune them for Simpsons character classification.
  * You can't use Transformers.
* Baseline:
  * The baseline used in this competition is a secret.
  * Your goal is to beat the baseline accuracy using your own model architecture and training strategy.
* Evaluation:
  * Models will be evaluated based on macro F1 score. 
  * You will be evaluated based on the leaderboard score.
 
### Hints

* Model Architecture:
  * Design an appropriate CNN architecture for image classification.
  * Experiment with different architectures, layers, and activation functions.
* Training Strategy:
  * Adjust hyperparameters, such as learning rate and batch size.
  * Consider data augmentation to improve model generalization.
  * Explore regularization techniques, such as dropout and batch normalization.
* Transfer Learning:
  * Leverage the power of transfer learning to improve your model's accuracy.
  * Consider using pre-trained models available in popular deep learning frameworks.

### Submission
To submit your solution create pull request to the `main` branch.

Ensure your final submission includes:
* Source code (simpsons_classification.py or similar).
* A brief report (report.md or similar) explaining your CNN architecture, training strategy, and any challenges faced.

### Evaluation

Your solution will be evaluated based on the accuracy achieved in the Kaggle competition. The goal is to classify Simpsons characters with high macro F1 score.

Good luck, and may the best model win! If you have any questions, feel free to reach out.
