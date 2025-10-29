🧠 Tamil Text Summarization using Large Language Models (LLMs)

📘 Overview

This repository contains the hands-on notebook used in the workshop session on Tamil Text Summarization using Large Language Models (LLMs).
It demonstrates how to apply multilingual transformer-based models such as mT5 and Tamil-BERT for summarization tasks in Tamil using the XL-Sum dataset.

🎯 Purpose

The goal of this session is to:
Understand how transformers perform text summarization for Tamil.
Explore pretrained multilingual and Tamil-specific LLMs.
Perform data preprocessing, fine-tuning, and evaluation (using ROUGE metrics).
Encourage researchers to build efficient, factual, and culturally aligned Tamil NLP applications.

👩‍💻 Author

Jayaraghavi R.
Research Scholar, Department of Computer Science and Engineering,
PSG College of Technology, Coimbatore, Tamil Nadu, India

🧩 Notebook

📄 File: tamil_llm_summ_handson.ipynb

This notebook includes:

Tokenization using transformers
Model loading (e.g., mT5-small, l3cube-pune/tamil-bert)
Generating Tamil summaries
ROUGE score evaluation

⚙️ Environment Setup (Google Colab Recommended)

Run the following cells in Google Colab before executing the notebook:
!pip install transformers datasets sentencepiece rouge-score torch

🤝 Acknowledgments

AI4Bharat for Tamil NLP datasets and models
L3Cube Pune for open Tamil BERT models
Google Research for the mT5 multilingual model
Hugging Face for open-source model hosting and tools

🧾 License

This repository is released under the MIT License.
You are free to use, modify, and distribute this work with appropriate credit.
