              LLM Text Preprocessing using Pandas, NLTK, and Regular Expressions

Project Overview:

This project demonstrates the fundamental text preprocessing techniques used in Large Language Models (LLMs) and Natural Language Processing (NLP). The objective is to clean raw text data, tokenize sentences, and prepare a structured dataset for further machine learning or NLP applications.

---

 Objective:

- Load a text dataset using Pandas.
- Clean textual data using Regular Expressions (re).
- Perform Sentence Tokenization using NLTK.
- Save the processed dataset as a new CSV file.
- Understand the preprocessing pipeline used in NLP and LLM tasks.

---

 Technologies Used:

- Python
- Pandas
- NLTK (Natural Language Toolkit)
- Regular Expressions (re)
- Google Colab

---

 Dataset:

The dataset contains sample social media text messages with:
- Normal text
- URLs
- Mentions (@username)
- Hashtags (#)
- Emojis

Dataset File:
- `spam.csv`

---

 Project Workflow:

1. Import Required Libraries
2. Load Dataset using Pandas
3. Explore Dataset
4. Handle Missing Values
5. Remove Duplicate Records
6. Clean Text using Regular Expressions
7. Convert Text to Lowercase
8. Remove URLs, Mentions, Hashtags, and Special Characters
9. Perform Sentence Tokenization using NLTK
10. Save the Cleaned Dataset as CSV

---

 Libraries Used:

```python
import pandas as pd
import re
import nltk
from nltk.tokenize import sent_tokenize
```

---

 Output Files:

- `spam.csv` – Original Dataset
- `cleaned_spam.csv` – Cleaned Dataset

---

Key Features:

- Text Cleaning
- Sentence Tokenization
- URL Removal
- Mention Removal
- Hashtag Removal
- Special Character Removal
- CSV Export

---

 Learning Outcomes:

Through this project, I learned:

- Text preprocessing techniques used in NLP.
- Working with Pandas Data Frames.
- Cleaning text using Regular Expressions.
- Sentence Tokenization using NLTK.
- Preparing datasets for future NLP and LLM applications.

---

 Conclusion:

Text preprocessing is an essential step in Natural Language Processing and Large Language Models. This project demonstrates how raw text data can be transformed into a clean and structured format suitable for analysis, machine learning, and language model training.

---

 Author

**Hari Priya B**

B.Sc. Computer Science with Artificial Intelligence
