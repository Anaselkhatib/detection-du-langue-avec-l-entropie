Language Detection Using Entropy
Overview

This project implements language detection based on Shannon entropy, supporting French, English, Spanish, and Italian. The approach analyzes character frequency distributions to determine the language of a given text.
Features

    Supports French, English, Spanish, and Italian
    Uses Shannon entropy for statistical language classification
    Processes both short and long text samples
    Implements multiple detection approaches

Installation
Clone the repository:

git clone https://github.com/Anaselkhatib/projet-theorie-info.git

cd language-detection-entropy

Install dependencies:

pip install -r requirements.txt

Usage

Run the script with a sample text:

python detect_language.py "Hola, ¿cómo estás?"

Example Output

Detected Language: Spanish (Entropy: 4.15)

Approaches

This project includes two different approaches to entropy-based language detection:

    First Approach: Basic character frequency analysis with entropy computation.
    Second Approach: Enhanced version with additional text preprocessing and optimizations.

Future Improvements

    Extend support to more languages
    Improve accuracy using N-grams
    Develop a web API for real-time detection

License
This project is open-source and available under the MIT License.
