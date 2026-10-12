# Phishing Detection Model

Machine learning-powered email phishing classifier using ensemble models, NLP feature extraction, and active learning with 96% detection accuracy.

## Features

- **Ensemble Models**: Random Forest + SVM + Neural Network voting
- **Email Analysis**: Header validation (SPF, DKIM, DMARC), sender reputation
- **NLP Processing**: TF-IDF, word embeddings, urgency pattern detection
- **URL Analysis**: Domain reputation, homoglyph detection, age scoring
- **Active Learning**: Analyst feedback for continuous model improvement
- **Confidence Scoring**: Per-email confidence with explainability

## Quick Start

```bash
git clone https://github.com/Korir555/phishing-detection-model.git
cd phishing-detection-model
pip install -r requirements.txt
python train.py
python predict.py --email sample.eml
```

## Performance

| Metric | Score |
|--------|-------|
| Precision | 96% |
| Recall | 92% |
| F1 Score | 94% |
| False Positive Rate | 2.1% |

## Technologies

scikit-learn | TensorFlow | Pandas | NLTK | spaCy | URL Reputation APIs

## Hiring Relevance

- Security ML engineering
- Email threat detection
- Model training and evaluation
- Threat prevention automation

## Documentation

Full model architecture and training guide: [Case Study](https://korir555.github.io/cybersecurity-portfolio/projects/08-phishing-detection-model/)

## License

MIT License
