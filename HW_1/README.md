# CSE 143 (Winter 2020) HW 1 data
# Mythili Karra, Abirami Patchaiyappan, Alexandra Luther
# N-Gram model
...
This folder contains 3 files, a subset of the 1 Billion Word Benchmark's
heldout set.

Specifically, `1b_benchmark.train.tokens` is taken from sections 0-9,
`1b_benchmark.dev.tokens` is taken from sections 10 and 11, and
`1b_benchmark.test.tokens` is taken from sections 12 and 13.

To download the raw 1 Billion Word Benchmark and generate the data, run:

```
./subsample_1b_benchmark.sh
```
...
This folder also contains the program A1.py which will create
unigram, bigram, and trigram models for the train file and implement
the same models on the dev and test files. When you run the
program, it calls on the main function which will print the
following data:
- the unigram, bigram, and trigram perplexities followed by the
results of smoothing with 5 different sets of hyperparameters for
each of the data sets
- following both the train and dev prints blocks, the program prints
the unigram probability of UNK tokens
    - to analyze a different threshold of UNK tokens change the
    value in arr_words (indicated by the comment # # change to 5
    for experiment)
- the perplexities for unigram, bigram, and trigram after the train
 data has been halved for each of the three data files

 ...
 This folder also contains a pdf document analyzing this program.
