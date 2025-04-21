
## 🚀 Project Name: **StoryWeaver AI**

Generate new story continuations from real human-written tales using a Bigram Language Model.

---

### 📖 Description

**StoryWeaver AI** is a simple yet powerful tool that generates story snippets using a Bigram-based text generation model. It leverages real stories from the [Kaggle dataset](https://www.kaggle.com/datasets/humairmunir/stories) to build a probabilistic model of word sequences and generate new text based on user input. It's a fun and educational project that demonstrates the basics of Natural Language Processing (NLP), specifically n-gram modeling.

---

### 💡 Features

- 📚 Automatically downloads and loads real-world stories using `kagglehub`.
- 🔤 Builds a Bigram language model from the dataset.
- ✍️ Generates story-like text given a starting word.
- 🧠 Simple, intuitive logic for educational and experimentation purposes.

---

### 📂 Dataset

This project uses the Kaggle dataset: [`humairmunir/stories`](https://www.kaggle.com/datasets/humairmunir/stories)  
Ensure you have access and authentication configured with `kagglehub`.

---

### 🛠️ Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/storyweaver-ai.git
cd storyweaver-ai
```

2. Install required libraries:

```bash
pip install kagglehub
```

> `kagglehub` may require authentication setup using your Kaggle API credentials.

---

### 🧪 Usage

Simply run the script:

```bash
python storyweaver.py
```

You will be prompted to enter a **starting word**. If the word exists in the dataset's vocabulary, the model will generate a short story-like continuation.

---

### 📝 Example

```bash
Enter a starting word: Once
Generated text: Once upon a time there was a little boy who loved to read books and tell stories to his friends
```

---

### 🧠 How It Works

1. All `.txt` files from the dataset are read and combined.
2. Text is tokenized and bigrams (two-word sequences) are created.
3. A dictionary maps each word to possible next words.
4. A random next word is selected from the possibilities to build a generated sentence.

---

### 📌 Future Improvements

- Upgrade to Trigram or Markov Chains for better generation.
- Clean punctuation and casing using `nltk` or `spaCy`.
- Add a web UI using Streamlit or Gradio.
- Add word embeddings or neural language models (e.g., GPT-based).

---

### 🤝 Contributing

Pull requests and improvements are welcome! Feel free to open issues or suggest new features.
