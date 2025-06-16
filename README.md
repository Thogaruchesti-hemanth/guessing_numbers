# 🎯 AI Number Guessing Game

An AI-powered number guessing game built using Python and Keras. The model is trained on a dataset from Kaggle to predict numbers based on input patterns. This project demonstrates a simple but effective use of deep learning for multi-class classification.

---

## 📌 Features

- 🧠 Neural network trained using Keras & TensorFlow
- 📊 Categorical classification using `categorical_crossentropy`
- ⚡ Optimized with Adam optimizer
- 🔢 Predicts numbers based on dataset patterns
- 🧪 Educational and beginner-friendly ML project

---

## 🗂️ Dataset

The dataset used for training was sourced from [Kaggle](https://www.kaggle.com/). Make sure to download and place it in the `data/` directory.

> 📁 Example Path: `./data/your_dataset.csv`

---

## 🛠️ Installation & Setup

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/ai-number-guessing-game.git
cd ai-number-guessing-game
```
## 🛠️ Installation & Setup

### Install dependencies:

```bash
pip install -r requirements.txt
```
### Run the training script 

```bash
python train.py
```
### Make predictions (after training):

```bash
python predict.py
```

## 📈 Model Summary

- **Input Layer:** Based on dataset features  
- **Hidden Layers:** Dense layers with activation functions  
- **Output Layer:** Softmax for multi-class classification  
- **Loss Function:** `categorical_crossentropy`  
- **Optimizer:** `adam`  
- **Metrics:** `accuracy`
---

## 📷 Demo *(Optional)*

Add a screenshot or a short CLI video/gif showing predictions, if available.

---

## 🤖 Tech Stack

- Python  
- TensorFlow / Keras  
- NumPy / Pandas  
- Matplotlib *(optional for visualization)*

---

## 🚀 Future Improvements

- Add a Streamlit web UI for user interaction  
- Improve dataset and model accuracy  
- Save/load model using `model.save()` and `load_model()`

---

## 🧑‍💻 Author

**Your Name**  
📧 saihemanth225@gmail.com  
🌐 [portfolio-link](https://protfolio-oa5n-git-update-9e2e5a-thogaruchestihemanths-projects.vercel.app/)

---

## ⭐ License

This project is licensed under the **MIT License**.

---

## 💬 Need Help?

Let me know if:

- You want to add your actual Kaggle dataset link  
- You want a sample `requirements.txt` file  
- You want the code files (`train.py`, `predict.py`) to match this README

I can generate them for you too.
