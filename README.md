# Bias in Bios

A CBS project on gender bias in machine learning. Using the public Bias in Bios dataset of short online biographies, we predict a person's occupation from the text and check whether the models treat men and women differently.

## What the notebook does

It loads the biographies, masks names with spaCy, and trains a bag-of-words baseline (logistic regression). It then compares accuracy and true-positive rate between men and women, tests dataset balancing as a way to reduce the gap, and compares the baseline with an LLM (OpenAI), discussing the fairness trade-offs.

## Files

BiasInBios.ipynb is the full analysis, built in Google Colab, with outputs.

## Note

The OpenAI key is read from Colab Secrets and is not part of this repository. To rerun the LLM part you need your own key.
