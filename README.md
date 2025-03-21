# 🚀 From Bi-grams to GPT: A Journey in Language Modeling

Welcome to **From Bi-grams to GPT**, a repository that explores the evolution of language models—starting from a simple statistical bigram model and progressing to a fully functional GPT-style transformer model, all implemented from scratch in PyTorch!

## 📂 Project Structure

```
📦 Your-Repository-Name
┣ 📜 gpt.py                 # A transformer-based language model (GPT-like)
┣ 📜 statistical_bigram.py   # A simple statistical bigram model
┣ 📜 input.txt               # Training dataset (Shakespeare text)
┣ 📜 README.md               # You're reading this! 😊
```

## 🧠 What's Inside?

### 1️⃣ **Bigram Model (**\`\`**)**

🔹 A simple statistical approach where the next token is predicted based on the previous one.\
🔹 Uses an embedding table where each token learns its next-token probabilities.\
🔹 Quick to train but lacks deep contextual understanding.

### 2️⃣ **GPT-like Transformer (**\`\`**)**

🚀 A modern language model with:\
✔ Multi-head self-attention for context awareness\
✔ Position embeddings to capture sequential order\
✔ Transformer blocks with layer normalization and dropout\
✔ Token generation using learned probabilities

## 🔧 Setup

1. **Clone the repo**

   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
   ```

2. **Install dependencies**

   ```bash
   pip install torch
   ```

3. **Train and Run the Models**

   - To train the **Bigram Model**:
     ```bash
     python statistical_bigram.py
     ```
   - To train the **GPT Model**:
     ```bash
     python gpt.py
     ```
## 🤖 Future Enhancements

- Train on larger datasets

- Implement a more advanced transformer architecture

- Experiment with different tokenization strategies



---

💡 **Inspired by Karpathy’s nanoGPT and transformer models, this project helps build an intuition for modern NLP.**

📢 If you find this useful, don’t forget to ⭐ **star this repo** and contribute! 🚀

