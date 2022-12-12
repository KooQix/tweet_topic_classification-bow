# Tweet Topic Classification (Simple Bag-of-Words)

2 datasets based on tweets related to Coronavirus Pandemic

## Phase 1 - Evaluate annotators and get true label

There are two parts: evaluating annotator agreement for each data file, and assembling the files together to come up with datasets where each text has a single label that can be used for modeling.

The 2 datasets are labeled by several annotators.

1. Evaluate annotator agreement (Kappa score) to determinate the label
2. Assemble datasets (changeorg & nyt) with true label

## Phase 2 - Create and train a simple model for topic classification

70% of first dataset used for training, the rest (30%) and the second dataset are used for testing

1. Create a simple bag-of-words classifier and evaluate
2. Feature engineering (try and add some features that might be associated with the category to predict in order to improve the performance)
