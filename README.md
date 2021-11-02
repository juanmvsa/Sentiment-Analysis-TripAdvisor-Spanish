# Bert-based Approach for Spanish Reviews from TripAdvisor
This repo contains the following:

- The paper describing our participation in the shared task: https://github.com/juanmvsa/Sentiment-Analysis-TripAdvisor-Spanish/blob/main/Bert-based%20Approach%20for%20Sentiment%20Analysis%20of%20Spanish%20Reviews%20from%20TripAdvisor.pdf
- Notebook with the experiments listed in Section 4: https://github.com/juanmvsa/Sentiment-Analysis-TripAdvisor-Spanish/blob/main/4.%20Experiments.ipynb
- Notebook for implementing the first system described in the paper: https://github.com/juanmvsa/Sentiment-Analysis-TripAdvisor-Spanish/blob/main/3.1%20Fine-tuned%20Bert%20approach.ipynb
- Notebook for implementing the second system described in the paper: https://github.com/juanmvsa/Sentiment-Analysis-TripAdvisor-Spanish/blob/main/3.2%20Fine-tuned%20Bert%20Approach%20with%20TF-IDF%20vectors.ipynb


## Notes:
- The notebook "3.1 Fine-tuned Bert approach" implements a fine-tuned version of Beto. Its output is a .txt file with the predicted classes on the test set.
- The notebook "3.2 Fine-tuned Bert approach" first implements a fine-tuned version of Beto. Then it extracts the TF-IDF features, concatenates both sets and uses logistic regression for the prediction of the classes in the test set.
- The data can be obtained from https://sites.google.com/cicese.edu.mx/rest-mex-2021/corpus-request?authuser=0


