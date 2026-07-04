# Automated Document Summarizer & Keyword Extractor

An enterprise text optimization pipeline designed to compress long data files, logs, or corporate documents into clear abstract summaries and isolate structural metadata tags.

## 🚀 Live Cloud Deployment
Click the badge below to load, initialize, and execute this project inside Google Colab via a secure, hardware-isolated cloud environment:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([PASTE_YOUR_PROJECT2_COLAB_URL_HERE](https://colab.research.google.com/drive/1okjchLJcXCeTL0lcXmHv0LmlBtfqH_YZ#scrollTo=v_CIhk7G02GY))

## 🛠️ Technology Stack
* **Summarization Core:** DistilBART Sequence-to-Sequence Attention Layer (`sshleifer/distilbart-cnn-12-6`)
* **Keyword Engine:** Tokenized word-frequency array counters via Python `re`
* **Infrastructure Layer:** PyTorch CUDA compute mapping over cloud T4 GPU matrices
