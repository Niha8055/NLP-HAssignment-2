# CS5760 Natural Language Processing
## Homework 2

**Student Name:** Niharika Mannepalli  
**Course:** CS5760 Natural Language Processing  
**Semester:** Fall 2026  

## Assignment Description

This homework covers text classification, Naive Bayes, bigram language models,
backoff models, evaluation metrics, and language model implementation.

## Programming Task

The programming portion implements a Bigram Language Model using Python.

The program:

- Reads the provided training corpus.
- Computes unigram counts.
- Computes bigram counts.
- Estimates bigram probabilities using Maximum Likelihood Estimation (MLE).
- Implements a function to calculate the probability of a sentence.
- Calculates probabilities for the two required test sentences.
- Compares the probabilities and determines which sentence the model prefers.

## Training Corpus

<s> I love NLP </s>

<s> I love deep learning </s>

<s> deep learning is fun </s>

## Test Sentences

S1:

<s> I love NLP </s>

S2:

<s> I love deep learning </s>

## Results

The calculated sentence probabilities are:

P(S1) = 0.3333

P(S2) = 0.1667

Since P(S1) > P(S2), the bigram language model prefers S1.

## Files

- `bigram_model-checkpoint.ipynb` — Jupyter Notebook containing the implementation and output.
- `README.md` — Description of the assignment, implementation, and results.

## How to Run

1. Open the Jupyter Notebook.
2. Run each cell in order.
3. The program prints the training corpus, unigram counts, bigram counts, MLE bigram probabilities, sentence probabilities, and the model preference.

## Conclusion

The Bigram Language Model assigns a higher probability to S1 than S2.
Therefore, the model prefers:

<s> I love NLP </s>
