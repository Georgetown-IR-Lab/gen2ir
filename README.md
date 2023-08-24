# gen2ir

This repository contains the code to reproduce results in the paper "Genetic Generative Information Retrieval" accepted at The 23rd ACM Symposium on Document Engineering (DocEng 2023).

The paper can be found here: https://dl.acm.org/doi/abs/10.1145/3573128.3609340

## Citation

If you use this code please cite the following paper:

```
@inproceedings{10.1145/3573128.3609340,
author = {Kulkarni, Hrishikesh and Young, Zachary and Goharian, Nazli and Frieder, Ophir and MacAvaney, Sean},
title = {Genetic Generative Information Retrieval},
year = {2023},
isbn = {9798400700279},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3573128.3609340},
doi = {10.1145/3573128.3609340},
abstract = {Documents come in all shapes and sizes and are created by many different means, including now-a-days, generative language models. We demonstrate that a simple genetic algorithm can improve generative information retrieval by using a document's text as a genetic representation, a relevance model as a fitness function, and a large language model as a genetic operator that introduces diversity through random changes to the text to produce new documents. By "mutating" highly-relevant documents and "crossing over" content between documents, we produce new documents of greater relevance to a user's information need --- validated in terms of estimated relevance scores from various models and via a preliminary human evaluation. We also identify challenges that demand further study.},
booktitle = {Proceedings of the ACM Symposium on Document Engineering 2023},
articleno = {8},
numpages = {4},
keywords = {genetic algorithm, generative information retrieval, large language models},
location = {Limerick, Ireland},
series = {DocEng '23}
}
```

## Run

Set the following parameters in the code:

```
  DEPTH: Termination Depth
  DOC_DEPTH: Sampling Depth
  no_of_mutations_per_iteration: mutation budget for each iteration
```

Run the above RQ files to obtain results for the corresponding Research Questions given in the paper.

## Data

MS Marco TREC DL 2019, TREC DL 2020 and Dev (small) datasets are used.

## Requirements

Python 3

OpenAI API Key
