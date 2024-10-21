# Landmark Papers in AI and Machine Learning

This repository contains papers on Machine Learning and AI which developed important techniques. It is not a exaustive guide, just a space where I share papers that I think are significant.

- [Retrieval Augmented Generation (RAG)](#retrieval-augmented-generation)
 - [General RAG Papers](#general-rag-papers)
 - [Summarization](#summarization)
 
## Retrieval Augmented Generation

### General RAG Papers

RAG (Retrieval-Augmented Generation) is a method that combines information retrieval and text generation. It works by retrieving relevant documents or data from a knowledge source (like a database or the web) and then using a language model to generate a response or summary based on that retrieved information. This approach enhances the accuracy and relevance of generated text, making it especially useful for answering complex questions, summarizing documents, or providing context-aware responses.

![alt text](http://url/to/img.png)

- **Searching for Best Practices in Retrieval-Augmented Generation (2024):** [**[Paper]**](https://arxiv.org/pdf/2407.01219) [**[Github]**](https://github.com/FudanDNN-NLP/RAG?tab=readme-ov-file)

### Evaluation

#### General Performance
#### Specific Domains
#### Retrieval Capability

### Fine-Tune

#### Disturb
#### Random
#### Normal

### Summarization

| Technique | Strategy |
| :--: | :--: |
| Recomp | Extractive & Abstractive |
| BM25 | Extractive |
| Contriever | Extractive |
| LongLLMlingua | Abstractive |
| SelectiveContext | Abstractive |

#### Recomp

Recompt in RAG refers to "recomposition," a process where the AI model retrieves relevant information from external sources (like documents or databases) and then generates a coherent summary by recomposing the retrieved content. It helps create more accurate, context-aware responses by combining information retrieval with text generation, making it useful for tasks like summarizing long or complex texts.

- **Recomp: Improving Retrieval-Augmented LMS With Compression and Selective Augmentation:** [**[Paper]**](https://arxiv.org/abs/2310.04408) [**[Github]**](https://github.com/carriex/recomp)

------
Ordering still:

##### RAG Improvements
- STaR: Self-Taught Reasoner Bootstrapping Reasoning With Reasoning (2024): [**[Paper]**](https://openreview.net/pdf?id=_3ELRdg2sgI) [**[Github]**](https://github.com/ezelikman/STaR)

#### Information Retrieval

##### TF-IDF

TF-IDF is used for keyword-based search in document collections, such as in basic search engines or in information filtering tasks. It is simple, fast, and effective for keyword-based tasks but	no semantic understanding, limited term frequency handling.

##### BM25

Widely used in modern search engines and information retrieval systems where document length and query term frequency normalization are important.

##### BM25+

An enhanced version of BM25 that corrects some of its biases, particularly regarding document length.

##### Language Models for Information Retrieval (LMIR)

Language models are used in more advanced search engines where the goal is to calculate the probability of a query being generated from a document’s "language model.

##### Vector Space Model (VSM)

Useful for information retrieval tasks where documents and queries can be represented as vectors in a multi-dimensional space (like document classification and clustering).

