# 💬 Sentiment Analysis

A real-time sentiment analysis tool powered by Hugging Face Transformers, deployed as an interactive Gradio web application. Enter any text and instantly get a positive/negative sentiment prediction with a confidence score.

---

## 📌 Overview

Sentiment analysis is a core NLP task with applications in customer feedback, social media monitoring, and brand analytics. This app wraps a pre-trained Hugging Face transformer model into a clean, accessible interface — no setup required for the end user.

**Key capabilities:**
- Real-time positive/negative sentiment classification
- Confidence score output for every prediction
- Clean Gradio interface accessible via browser
- Built on pre-trained transformer pipeline (no custom training required)

---

## 🛠 Tech Stack

| Component | Technology |
|---|---|
| Model | Hugging Face Transformers (sentiment-analysis pipeline) |
| Frontend | Gradio |
| Language | Python |

---

## ⚙️ How to Run Locally

```bash
# Clone the repo
git clone https://github.com/Sudha0626/Sentiment_Analysis.git
cd Sentiment_Analysis

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
```

---

## 📁 Project Structure

```
Sentiment_Analysis/
├── app.py              # Gradio app + transformer pipeline
├── requirements.txt    # Dependencies
└── README.md
```

---

## 🖥 Sample Output

```
Input:  "I absolutely love how this product works!"
Output: POSITIVE (Score: 0.9998)

Input:  "This was a terrible experience."
Output: NEGATIVE (Score: 0.9985)
```

---

## 🌱 Future Improvements

- Add multi-class sentiment (positive / neutral / negative)
- Support batch text input for bulk analysis
- Fine-tune on domain-specific datasets (e.g. financial news, product reviews)

---

## 👩‍💻 Author

**Raaga Sudha** — [LinkedIn](https://linkedin.com/in/raagasudha06) · [GitHub](https://github.com/Sudha0626)
