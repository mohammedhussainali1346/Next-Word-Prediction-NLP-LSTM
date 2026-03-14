Next Word Prediction using LSTM

This project explores how deep learning models can learn patterns in language and predict the **next word in a sentence**.

The models were trained on text from Shakespeare's *Hamlet* using the **NLTK Gutenberg corpus**. By learning the sequence patterns in the text, the model can take a phrase like:

`To be or not to`

and predict the most likely next word.

---

Project Motivation

Language models are a fundamental part of modern AI systems such as chatbots, autocomplete tools, and text generation models.

This project was created to better understand:

* How sequence models process text
* How LSTM networks handle sequential data
* How to deploy deep learning models with Streamlit

---

Project Structure

```
Next-Word-Prediction-NLP-LSTM
│
├── next_word_LSTM.py
├── next_word_lstm.h5
├── tokenizer.pickle
│── requirements.txt
└── README.md
```

---

Technologies Used

* Python
* TensorFlow / Keras
* NLTK
* NumPy
* Streamlit

---

How the Model Works

1. The text dataset is cleaned and tokenized.
2. Word sequences are created from the corpus.
3. Each sequence is padded to a fixed length.
4. The neural network learns to predict the next word given a sequence.
5. During inference, the model selects the word with the highest probability.

---


Run the Streamlit app:


https://next-word-prediction-nlp-lstm-yzjkjvettzjezvmg3bhsuw.streamlit.app/


---

Example

Input:

```
To be or not to
```

Output:

```
Next word: be
```

(The exact prediction depends on the trained model.)

---

Author

Mohammed Hussain Ali

This project was built as part of my learning journey in **Natural Language Processing and Deep Learning**.

---

