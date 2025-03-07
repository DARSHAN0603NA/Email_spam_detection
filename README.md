
# Email Spam Classifier

This project uses a Naive Bayes model to classify emails as Spam or Ham. It leverages a CountVectorizer for text processing and offers an interactive Gradio interface to input emails, view predictions, and analyze performance metrics.

## Features

- Classify emails as Spam or Ham
- Highlight spammy keywords (e.g., "win", "free", "urgent")
- Display confidence score and advice
- View model performance metrics (Accuracy, Precision, Recall, F1 Score)
- Retrain the model with new email data

## Setup

1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Gradio interface:
   ```bash
   python app.py
   ```

## License

MIT License - see [LICENSE](LICENSE).

---

