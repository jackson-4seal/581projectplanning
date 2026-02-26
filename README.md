# 581projectplanning

## Choosing a task

My initial decision is to work on task 2, dialect identification. I may attempt task 4, fake image detector.

## Methodology

## TODO: study ml practices module


## Task 2

### Background

[2]
- Dialect is the combination of grammatical, lexical, and phonological variation in pronunciation. 
- Accent, on the other hand, is only related to pronunciation.
- "The approaches to dialect identification are similar to those used in language identification."
- Two approaches to modeling classes: acoustic and phonotactic.
- Acoustic modeling -- related to spectral feature modeling
- Phonotactic approach -- related to phone recognition, language models, and subsequent scoring


#### Phonotactic Modeling
[2]
Popular approach is phone recognition followed by language modeling (PRLM). audio -> phonemes -> n-gram LM.
Utterance gets tokenized using the phone recognizer and passed to the LM. Dialect that yields the highest score using the sequence of phonemes is the hypothesized dialect (output).

If data is limited, another approach using a bank of phone recognizers and language models is used. (PPRLM)


#### Acoustic Modeling
[2]
Usually a Gaussian Mixture Model (GMM). Extract relevant features directly from the acoustic data.

#### Dialect ID

According to [2], dialect is the most compelx aspect of speech recognition. Also worth noting is that dialects are not static, they change with place and time.

[5] used a GMM to identify chinese accents, feeding in MFCC feature vectors


### Approach




### Data


### Results


### Citations

    1. [Hybrid CNN–LSTM deep learning for Telugu dialect identification using a curated speech corpus (2026)](https://link.springer.com/article/10.1007/s10772-025-10249-2)
    2. [Language and Dialect Identification: A survey (2015)](https://ieeexplore.ieee.org/document/7361147)
    3. [Comparison of four approaches to automatic language identification of telephone speech (1996)]
    4. [Acoustic, phonetic, and discriminative approaches to automatic language identification (2003)]
    5. [Automatic accent identification using Gaussian Mixture Models (2001)]




## Task 4

### Approach


### Citations

    1. [Performance Comparison and Visualization of AI-Generated-Image Detection Methods](https://ieeexplore.ieee.org/abstract/document/10508937)