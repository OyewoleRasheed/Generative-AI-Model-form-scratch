````markdown
# 🧠 Generative AI Model from Scratch with Python

This project replicates the tutorial from [AmanXAI](https://amanxai.com/2024/08/05/generative-ai-model-from-scratch-with-python/), where a **generative text model** is built entirely from scratch using Python, NumPy, and basic neural network principles — without high-level deep learning frameworks like TensorFlow or PyTorch.

It demonstrates how to manually implement a minimal character-level RNN to generate text from a corpus using forward and backward propagation.

---

## ✨ Features

- Character-level text generation
- Manual implementation of:
  - One-hot encoding
  - Forward propagation
  - Backpropagation Through Time (BPTT)
  - Weight updates via SGD
- Fully written using **Python + NumPy**
- Generates creative text from any seed

---

## 🛠 Requirements

- Python 3.7+
- NumPy

Install dependencies:

```bash
pip install numpy
````

---

## 🚀 How to Run

1. Add your training corpus in a file named `input.txt`.

2. Run the training script:

```bash
python generative_rnn.py
```

3. After training, use the script to generate text:

```python
generate_text("once upon", length=100)
```

This will output a continuation of the seed string using the trained RNN.

---

## 📂 Project Structure

```
├── input.txt            # Training corpus
├── building-generative-ai-model-from-scratch.ipynb    # Core RNN model and training logic
├── README.md            # Project documentation
```

---

## 📈 Example Output

```
Seed: "deep learning"
Generated: "deep learning is a simple that the time is to the time the same and the some to the time"
```

---

## 🧠 Learning Objectives

* Understand how RNNs work under the hood
* Learn about hidden states, weight matrices, and time steps
* Experience implementing a generative model without external ML libraries

---

## ✅ Acknowledgments

Based on the tutorial by [AmanXAI](https://amanxai.com/2024/08/05/generative-ai-model-from-scratch-with-python/). Inspired by early character-level RNNs like those from Andrej Karpathy.

---

## 📝 License

This project is open for educational and research use.

```
