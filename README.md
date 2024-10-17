Overview
The Azure Text Analytics App is a Streamlit application that leverages Azure's Text Analytics API to analyze text for language detection, sentiment analysis, key phrases extraction, entity recognition, and linked entity recognition. This app allows users to either enter text manually or upload a text file for analysis.
Features
Language Detection: Automatically identifies the primary language of the input text.
Sentiment Analysis: Analyzes the overall sentiment of the text and provides confidence scores for positive, neutral, and negative sentiments.
Key Phrases Extraction: Extracts important phrases from the text.
Entity Recognition: Identifies entities present in the text and categorizes them.
Linked Entity Recognition: Recognizes entities and links them to external data sources, providing additional context.
Requirements
To run this application, you will need:
Python 3.7 or higher
Streamlit
Azure SDK for Python
python-dotenv
