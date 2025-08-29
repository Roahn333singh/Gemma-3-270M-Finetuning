

# 📚 Fine-Tuning Gemma 3-270M on Tiny Stories

![Hugging Face](https://img.shields.io/badge/HuggingFace-Transformers-orange?logo=huggingface)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?logo=pytorch&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

This project demonstrates **fine-tuning of Google’s Gemma 3-270M model** on the **Tiny Stories dataset** for improved story generation.  
By leveraging **Multi-Query Attention (MQA)** and **Sliding Window Attention (SWA)**, the model achieves **efficient memory usage** and **better narrative coherence**.  

---

## 🚀 Key Features
- 🔹 Fine-tuned **Gemma 3-270M** on [Tiny Stories](https://huggingface.co/datasets/roneneldan/TinyStories).  
- 🔹 Integrated **Multi-Query Attention (MQA)** for faster inference & reduced GPU memory.  
- 🔹 Applied **Sliding Window Attention (SWA)** for handling long-context sequences.  
- 🔹 Enhanced **story generation quality** with more consistent narratives.  

---

## 🛠️ Tech Stack
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)  
- [Datasets](https://huggingface.co/docs/datasets/)  
- [PyTorch](https://pytorch.org/)  
- Python 3.11+  

---

## 📂 Project Structure
├── gemma-3-270m.ipynb # Notebook for fine-tuning
├── data/ # Dataset (Tiny Stories)
├── outputs/ # Model checkpoints and logs
├── requirements.txt # Dependencies
└── README.md # Project documentation

---

## ⚙️ Setup

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/gemma-tinystories.git
cd gemma-tinystories
pip install -r requirements.txt


---

## ⚙️ Setup

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/gemma-tinystories.git
cd gemma-tinystories
pip install -r requirements.txt
```
🔮 Future Work

Explore LoRA fine-tuning for parameter-efficient training.

Extend dataset to longer narrative texts.

Experiment with RLHF (Reinforcement Learning with Human Feedback).

