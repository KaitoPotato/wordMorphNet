# Verb Learning Model: Regular and Irregular Past Tense Prediction

## Overview
This project explores how a neural network (perceptron) can learn and predict the transformation of verbs from their base form to their past tense. The model is trained on a dataset of verbs categorized into regular and irregular groups and further grouped into eight different classes based on their transformation rules. 

The goal is to analyze how well the perceptron generalizes its learning, replicating patterns observed in human language acquisition. The project also includes experiments with novel verbs to evaluate the model’s predictive capabilities.

## Features
- **Training a Perceptron Model**: The model is trained using sets of verbs categorized by frequency (high, medium, and low).
- **Irregular Verb Classification**: Irregular verbs are grouped into eight different transformation patterns.
- **Evaluation Metrics**: The perceptron is evaluated on its accuracy in predicting both regular and irregular verb transformations.
- **Visualization**: Various graphs are plotted to illustrate the learning curves for different verb classes.
- **Generalization with Novel Verbs**: The model is tested on novel words to assess its ability to predict regular vs. irregular past tense forms.

## Files and Structure
- `Assignment1_Part0.ipynb` - Preprocessing and categorization of verbs into regular and irregular groups.
- `Assignment1_Part1.ipynb` - Training, evaluation, and visualization of the perceptron model.

## Installation & Dependencies
Ensure you have Python and the following dependencies installed:
```bash
pip install numpy matplotlib
```

## Usage
1. Open and run `Assignment1_Part0.ipynb` to preprocess and categorize the verbs.
2. Open and run `Assignment1_Part1.ipynb` to train the perceptron and analyze results.
3. Review the generated plots to understand the model's performance across different verb classes.

## Results Interpretation
- Higher accuracy on regular verbs indicates that the model easily learns systematic transformations.
- Different learning rates for irregular verb classes suggest varying levels of difficulty in learning these transformations.
- The performance on novel words helps assess whether the model can generalize beyond the training data.

## Future Improvements
- Experiment with different neural network architectures.
- Expand the dataset with more verb transformations.
- Incorporate phonetic features for a more linguistic approach.

---

Let me know if you'd like any modifications or additional details in the README!