# CAS2105_Assignment-6
Mini AI Pipeline Project

1. Introduction
   Task: Classify short SMS messages as spam or not spam (ham).
   Motivation: A Simple and practical classification problem that is easy to reproduce and demonstrates building an AI pipeline: naive baseline, pre-trained-model-based pipeline, evaluation, and reflection.
   Input/Output: Input SMS text (string). Output: label in {spam, ham}.
   Success Criteria: The system should outperform a naive keyword-based baseline on accuracy and F1 on a held-out test set (first 200 entries, split as described below)


2. Dataset
   Source: SMS Spam Collection. For reproducibility in this project we use the first 200 rows of the dataset.
   Number of examples: 200 total
   Split:
   Train: first 150 examples
   Test: last 50 examples
   Preprocessing:
   Lowercasing
   Basic whitespace trimming
   No heavy text cleaning(to keep natural distribution)


3. Methods
