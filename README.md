<h1> English to Arabic Translator </h1>

<h3>Overview
This Streamlit app translates English words into Arabic using a pre-trained model based on a bilingual dictionary.
</h3>

Requirements
Python 3.6 or later
Streamlit
scikit-learn
pandas

<h4>Installation</h4>
Clone the repository:

git clone https://github.com/AlyaAlsalamah/appp.git

<h4>Install dependencies:</h4>

pip install -r requirements.txt

<h4>Run the Streamlit app:</h4>

streamlit run app.py

<h4>Usage </h4>
Enter an English word in the provided text input.
Click the "Translate" button to see the Arabic translation.

<h4>Model Details</h4>
The app uses a machine learning model based on a Random Forest classifier with a TF-IDF vectorizer. The model has been trained on a sample bilingual dictionary.

<h4>File Structure</h4>
app.py: The main Streamlit app script.
english_arabic_dictionary.csv: The sample bilingual dictionary.
requirements.txt: List of Python dependencies.

*Note*
*The app may not have translations for all English words, and if the entered word is not available, it will display a message indicating so.*
