# Hugging-Face-Pipeline-Tutorial

This repository contains a hands-on tutorial on using the **Hugging Face Transformers `pipeline` API** for various Natural Language Processing (NLP) tasks.  

The tutorial is implemented in the Jupyter notebook: **`Hugginface_pipline.ipynb`**.

---

## 📌 Overview
The Hugging Face `pipeline` API provides a simple, high-level interface to state-of-the-art models. With just a few lines of code, you can perform tasks such as:

- ✅ Sentiment Analysis  
- ✅ Masked Language Modeling (Fill-Mask)  
- ✅ Text Generation  
- ✅ Question Answering  
- ✅ Translation & Summarization  

This notebook walks you through each of these tasks step-by-step.

---

## 📂 Repository Contents
- **`Hugginface_pipline.ipynb`** → Main tutorial notebook with examples.  
- **README.md** → Project description and usage guide.  

---

## ⚙️ Installation

Make sure you have Python 3.8+ installed. Then install the dependencies:

```bash
pip install transformers torch
```

For GPU acceleration (optional, recommended if CUDA is available):

```bash
pip install torch --index-url https://download.pytorch.org/whl/cu121
```

---

## ▶️ Usage

1. Clone this repository:

```bash
git clone https://github.com/your-username/Hugging-Face-Pipeline-Tutorial.git
cd Hugging-Face-Pipeline-Tutorial
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook Hugginface_pipline.ipynb
```

3. Run the cells to explore different Hugging Face pipeline examples.

---

## 📖 References
- [Hugging Face Transformers Documentation](https://huggingface.co/docs/transformers)  
- [Pipeline API Guide](https://huggingface.co/docs/transformers/main_classes/pipelines)  

---

✨ Explore the notebook and experiment with different models to get a feel for how Hugging Face makes NLP super easy!  
