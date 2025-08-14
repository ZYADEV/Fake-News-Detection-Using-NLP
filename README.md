# Fake News Detection Using NLP

This project is a web application for classifying news as Fake or Real using Natural Language Processing (NLP) and a pre-trained machine learning model.

## Features
- User-friendly web interface built with Streamlit
- Text preprocessing (tokenization, stopword removal, lemmatization)
- Visual probability indicator for prediction
- Uses a pre-trained model for classification
## DEMO

<div>
  <img src="https://github.com/YOUNESSZYADImiaad/Fake-News-Detection-Using-NLP/assets/128265213/d27de1a9-c011-4aa4-9689-7320bbbe5fd8">
</div>

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd Fake-News-Detection-Using-NLP
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Download NLTK resources:**
   Run the following Python commands once to download required NLTK data:
   ```python
   import nltk
   nltk.download('stopwords')
   nltk.download('wordnet')
   ```
4. **Run the application:**
   ```bash
   streamlit run app.py
   ```

## Usage
- Enter news content in the text area.
- Click "Predict The News" to get the result.
- The app will display whether the news is Fake or Real, along with a probability indicator.

## Model
- The pre-trained model is located at `Model/model.pkl`.

## Troubleshooting
- Ensure all dependencies are installed.
- Make sure NLTK resources are downloaded.
- For issues, check the error messages or contact the repository owner.

## License
This project is for educational purposes.
