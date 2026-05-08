# 🧠 RNN Next Word Predictor

A Deep Learning based Next Word Prediction system built using **SimpleRNN** and **Natural Language Processing (NLP)** techniques in TensorFlow/Keras.  
The model predicts the next probable word from a given text sequence.

---

# 🚀 Project Overview

This project demonstrates how Recurrent Neural Networks (RNN) can be used for sequence prediction tasks in NLP.

The model is trained on a real-world text dataset and learns language patterns to predict the next word in a sentence.

Example:

Input:
```text
deep learning is
```

Output:
```text
powerful
```

---

# 🔥 Features

- ✅ Next Word Prediction
- ✅ NLP Text Preprocessing
- ✅ Tokenization
- ✅ Sequence Generation
- ✅ Padding Sequences
- ✅ SimpleRNN Deep Learning Model
- ✅ Real-world Dataset Training
- ✅ Model Saving & Loading
- ✅ TensorFlow/Keras Implementation

---

# 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| TensorFlow | Deep Learning Framework |
| Keras | Neural Network API |
| NumPy | Numerical Operations |
| Pandas | Data Handling |
| NLP | Text Processing |

---

# 🧠 Deep Learning Concepts Used

- Recurrent Neural Networks (RNN)
- Sequence Learning
- Word Embedding
- Tokenization
- Padding
- Softmax Activation
- Sparse Categorical Crossentropy

---

# 📂 Project Structure

```text
RNN-Next-Word-Predictor/
│
│
├── next_word_rnn_model.h5
│
├── RNN_model.ipynb
│
├── Sherlock Holmes.csv
│
├── README.md

```

---

# 📥 Dataset

Dataset used:
- Sherlock Holmes Text Dataset

The dataset contains large text sequences used for training the RNN model.

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/kanha165/RNN-Next-Word-Predictor.git
```

---

## 2️⃣ Move Into Project Folder

```bash
cd RNN-Next-Word-Predictor
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run Project

```bash
python app.py
```

OR run Jupyter notebook:

```bash
jupyter notebook
```

---

# 📖 Step-by-Step Workflow

```text
Dataset
   ↓
Text Cleaning
   ↓
Tokenization
   ↓
Sequence Generation
   ↓
Padding
   ↓
RNN Model Building
   ↓
Training
   ↓
Prediction
```

---

# 🧪 Model Architecture

```text
Input Text
     ↓
Embedding Layer
     ↓
SimpleRNN Layer
     ↓
Dense Layer (Softmax)
     ↓
Next Word Prediction
```

---

# 📌 Model Details

| Layer | Purpose |
|---|---|
| Embedding | Converts words into vectors |
| SimpleRNN | Learns sequence patterns |
| Dense | Predicts next word |

---

# 📊 Training Details

| Parameter | Value |
|---|---|
| Epochs | 20 |
| Batch Size | 128 |
| Optimizer | Adam |
| Loss Function | Sparse Categorical Crossentropy |

---

# 🧠 Example Prediction

## Input

```text
machine learning is
```

## Output

```text
powerful
```

---

# 💾 Save Trained Model

```python
model.save("next_word_rnn_model.h5")
```

---

# 📂 Load Saved Model

```python
from tensorflow.keras.models import load_model

model = load_model("next_word_rnn_model.h5")
```

---

# 🔥 Future Improvements

- ✅ Replace SimpleRNN with LSTM
- ✅ Add GRU Model
- ✅ Build Streamlit Web App
- ✅ Add Multiple Word Prediction
- ✅ Deploy on Cloud
- ✅ Add Voice Input

---

# 📸 Screenshots

Add your project screenshots here.

Example:
- Training Output
- Prediction Result
- Web UI

---

# 📚 Learning Outcomes

From this project, you will learn:

- Deep Learning Basics
- Recurrent Neural Networks
- NLP Pipeline
- Sequence Modeling
- TensorFlow/Keras
- Text Prediction Systems

---

# 🤝 Contribution

Contributions are welcome.

Feel free to:
- Fork the repository
- Improve the project
- Create pull requests

---



---

# 👨‍💻 Author

## Kanha Patidar

B.Tech CSIT Student  
Deep Learning & AI Enthusiast

---

# ⭐ Support

If you like this project:

- ⭐ Star this repository
- 🍴 Fork this repository
- 🧠 Share with others

---

# 🔥 Final Output

This project successfully builds a real-world:

# ✅ RNN-based Next Word Prediction System

using:
- NLP
- Deep Learning
- TensorFlow/Keras
- Sequence Learning
