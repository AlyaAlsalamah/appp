<h1> English to Arabic Translator </h1>

<h3>Overview
This Streamlit app translates English words into Arabic using a pre-trained model based on a bilingual dictionary.
</h3>

Requirements <br>
Python 3.6 or later<br>
Streamlit<br>
scikit-learn<br>
pandas

<h4>Installation</h4><br>
Clone the repository:<br>
git clone https://github.com/AlyaAlsalamah/appp.git<br>

<h4>Install dependencies:</h4><br>
pip install -r requirements.txt<br>

<h4>Run the Streamlit app:</h4><br>
streamlit run app.py<br>

<h4>Usage </h4><br>
Enter an English word in the provided text input.<br>
Click the "Translate" button to see the Arabic translation.<br>

<h4>Model Details</h4><br>
The app uses a machine learning model based on a Random Forest classifier with a TF-IDF vectorizer. The model has been trained on a sample bilingual dictionary.<br>

<h4>File Structure</h4><br>
 -app.py: The main Streamlit app script.<br>
 -english_arabic_dictionary.csv: The sample bilingual dictionary.<br>
 -requirements.txt: List of Python dependencies.<br> 

*Note*<br>
*The app may not have translations for all English words, and if the entered word is not available, it will display a message indicating so.*
