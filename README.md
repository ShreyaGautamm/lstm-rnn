# 🔮 Next Word Prediction with LSTM
A deep learning project that predicts the **next word** in a given sentence using **LSTM (Long Short-Term Memory)** networks. Trained on Shakespeare’s *Hamlet*, this model captures the language patterns of classic English literature.

---

## 📽️ Demo Preview
![Demo](streamlit_app/lstm-next-word-gif.gif)

---

## 📚 Dataset Details
This project uses the public domain text of *Hamlet* by William Shakespeare, comprising approximately 30,000 words of rich, poetic language. It offers a diverse vocabulary, poetic structure, and syntactic variety—perfect for testing a language model’s understanding of context and sequence.
- **Preprocessing:**
  - Converted to lowercase
  - Removed special characters and punctuation
  - Tokenized and converted to n-gram sequences \



## 🌟 Project Highlights
⚙️ **Preprocessing:** 
  - Tokenization of text into sequences  
  - Padding to ensure uniform input size  
  - Train/test split for evaluation

🧠 **Model Architecture:**  
  - `Embedding` → `LSTM (150)` → `Dropout` → `LSTM (100)` → `Dense (Softmax)`

🏋️ **Training:**  
  - Optimized with `Adam`, monitored using **EarlyStopping**  
  - Loss function: `Categorical Crossentropy`

✅ **Evaluation:**  
  - Tested on real prompts for word continuation accuracy

🌐 **Deployment:**  
  - Interactive **Streamlit web app** for real-time prediction


## 💻 Technologies Used

<p align="left">
  <a href="https://www.python.org/" target="_blank"><img src="https://www.vectorlogo.zone/logos/python/python-icon.svg" width="40" height="40" alt="Python"/></a>
  <a href="https://www.tensorflow.org/" target="_blank"><img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" width="40" height="40" alt="TensorFlow"/></a>
  <a href="https://keras.io/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/keras/keras-original.svg" width="40" height="40" alt="Keras"/></a>
  <a href="https://pandas.pydata.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" width="40" height="40" alt="Pandas"/></a>
  <a href="https://numpy.org/" target="_blank"><img src="https://www.vectorlogo.zone/logos/numpy/numpy-icon.svg" width="40" height="40" alt="NumPy"/></a>
  <a href="https://matplotlib.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" width="40" height="40" alt="Matplotlib"/></a>
  <a href="https://streamlit.io/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/streamlit/streamlit-original.svg" width="40" height="40" alt="Streamlit"/></a>
  <a href="https://colab.research.google.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecolab/googlecolab-plain.svg" width="40" height="40" alt="Google Colab"/></a>
</p>
