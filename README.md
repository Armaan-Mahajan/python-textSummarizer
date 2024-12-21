It looks like the formatting for the Setup section wasn’t properly enclosed in markdown syntax. Let me correct that for you:

# Text Summarizer with Gemini API and Text-to-Speech

This project is a simple text summarizer that uses the Google Gemini API to summarize input text in a user-defined number of words. It also includes a text-to-speech feature to read the summary aloud using the gTTS (Google Text-to-Speech) library.

## Requirements

- Python 3.x
- `google-generativeai` (Gemini API)
- `gtts`
- `pygame`
- `tkinter`

You can install the necessary libraries using pip:

```bash
pip install google-generativeai gtts pygame
```
## Setup
- Gemini API Key: To use the Google Gemini API, you’ll need to insert your API key into the code. You can get your key from the Gemini API Documentation.
- Run the Application: The app provides a graphical interface using tkinter where you can input text to be summarized, specify the number of words in the summary, and then have the summary read aloud.

## Features
- Text Input: Enter the text you wish to summarize
- Word Count Slider: Choose the number of words in the summary using a slider
- Summarize Button: Summarizes the input text using the Gemini API
- Read Aloud Button: Reads the summary aloud using Google Text-to-Speech (gTTS)

## How to Use
1. Enter the text to summarize in the input box
2. Adjust the slider to select the number of words in the summary
3. Click the “Summarize” button to generate the summary
4. Click the “Read aloud” button to listen to the summary
