# Unseen feature synthesis for Zero Shot Object Detection
This project is done as part of _CS435: Deep Learning with Computer Vision Applications_.

## Objective
We aim to utilize zero-shot detection, a machine learning approach, to develop a model capable of identifying objects or concepts it has neither encountered nor been trained on. This is accomplished by applying prior knowledge or learned representations, such as semantic embeddings, to generalize across unseen classes.

## Key Aspects of Zero-Shot Detection
- **Unseen Classes:** The model can recognize objects from categories it was not explicitly trained on with labeled examples.

- **Knowledge Transfer:** It relies on shared representations or mappings (e.g., word embeddings or attribute descriptions) to bridge the gap between seen and unseen classes for accurate predictions.

## Applications
Zero-shot detection is particularly useful for identifying rare or novel object categories. For example, in this project, we use it to detect mythical creatures like unicorns and phoenixes.

## Example
In a zero-shot detection system trained on animals like cats and dogs
If the system is introduced to a new class like lion, it can detect and classify lions by understanding its semantic similarity to known animals (e.g., lions are closer to cats in the semantic embedding space).

## Kaggle Notebook
[Notebook](https://www.kaggle.com/code/tiyagupta/cs435-project-final)
