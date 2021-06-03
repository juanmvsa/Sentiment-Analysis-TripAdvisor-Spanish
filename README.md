# Bert-based Approach for Spanish Reviews from TripAdvisor
This repo contains the following:

- Notebook with the experiments listed in Section 4.
- Notebook for implementing the first system listed on the paper.
- Notebook for implementing the second system listed on the paper.
- Training data provided in the competition.
- Test data provided in the competition.

## Notes:
- The notebook "3.1 Fine-tuned Bert approach" implements a fine-tuned version of Beto. Its output is a .txt file with the predicted classes on the test set.
- The notebook "3.2 Fine-tuned Bert approach" first implements a fine-tuned version of Beto. Then it extracts the TF-IDF features, concatenates both sets and uses logistic regression for the prediction of the classes in the test set.
