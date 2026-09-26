# <img src="https://slackmojis.com/emojis/30773-bert/download" width="55"> BERT NLP Tasks

Implementation of **U2T01: Adapting BERT for NLP Tasks**.

This repository contains the notebooks used to adapt `bert-base` to four classical NLP tasks. The files for each task are organized in the `tasks_files` directory, while the corresponding fine-tuned models are published on Hugging Face.

## Hugging Face Models

### [Topic Classification](https://huggingface.co/karencardiel/topic-classification-bert)

Classifies news articles into one of four predefined topics using the **AG News** dataset.

### [Named Entity Recognition (NER)](https://huggingface.co/Perry-DLC/upy-tds-bert-ner-conll2003)

Identifies and classifies named entities within text using the **CoNLL-2003** dataset.

### [POS Tagging](https://huggingface.co/ramiroc3/tds-bert-pos-ewt)

Assigns a part-of-speech tag to each token using the **UD English Web Treebank (EWT)** dataset.

### [Extractive Question Answering](https://huggingface.co/BradechiO/tds-bert-qa-squad)

Finds the answer span within a given context for a question using the **SQuAD** dataset.

