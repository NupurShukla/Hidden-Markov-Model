# Hidden-Markov-Model

This was implemented as part of course CSCI 567 (Machine Learning) in Spring 2018 at USC.

Model parameters - 
hmm_model.json, has the following model parameters: the initial probabilities (pi), the transition probabilities(A), the observation probabilities(B)

I have implementedthe forward algorithm and the backward algorithm to compute the probability of observing the sequence. Then I implemented Viterbi algorithm to infer the most likely state path

To run -
python3 hmm.py hmm_model.json AGCGTA | tee hmm.txt
