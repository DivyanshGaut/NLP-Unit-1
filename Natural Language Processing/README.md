# NLP Unit 1 Programs

This repository contains the six Natural Language Processing (NLP) programs required for Unit 1.

## Programs

| No. | Program | File |
|---|---|---|
| 1 | Tokenization using NLTK and spaCy | `01_Tokenization/tokenization.py` |
| 2 | Stemming and Lemmatization | `02_Stemming_Lemmatization/stemming_lemmatization.py` |
| 3 | Stop-word Removal | `03_Stopword_Removal/stopword_removal.py` |
| 4 | Part-of-Speech (POS) Tagging | `04_POS_Tagging/pos_tagging.py` |
| 5 | Parsing and Chunking using RegEx and spaCy | `05_Parsing_Chunking/parsing_chunking.py` |
| 6 | Named Entity Recognition (NER) using spaCy | `06_NER/ner.py` |

## Requirements

- Python 3.9 or above
- NLTK
- spaCy
- spaCy English model: `en_core_web_sm`

## Installation

Open a terminal in the repository folder and run:

```bash
pip install nltk spacy
python -m spacy download en_core_web_sm
```

## How to Run

Example:

```bash
python 01_Tokenization/tokenization.py
```

Similarly, run the other programs:

```bash
python 02_Stemming_Lemmatization/stemming_lemmatization.py
python 03_Stopword_Removal/stopword_removal.py
python 04_POS_Tagging/pos_tagging.py
python 05_Parsing_Chunking/parsing_chunking.py
python 06_NER/ner.py
```

## Concepts Covered

### 1. Tokenization
Breaking text into smaller units such as sentences and words.

### 2. Stemming
Reducing words to a root-like form using algorithms such as Porter Stemmer.

### 3. Lemmatization
Reducing words to their dictionary/base form using linguistic information.

### 4. Stop-word Removal
Removing common words such as "the", "is", "and", etc. when they are not useful for a particular NLP task.

### 5. POS Tagging
Assigning grammatical categories such as noun, verb, adjective, and adverb to words.

### 6. Parsing and Chunking
Analyzing grammatical structure and grouping words into meaningful phrases such as noun phrases.

### 7. Named Entity Recognition
Identifying entities such as people, organizations, locations, dates, and companies.

## Author

NLP Unit 1 Practical Programs
