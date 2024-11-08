# Document Translation with Microsoft Translator API

This project translates text and `.docx` documents from English to a specified target language using the Microsoft Translator API. The translated content is saved as a new document.

## Features
- Translate text from English to the target language.
- Translate `.docx` files and save them with translated content.
- Customizable destination language.

## Setup and Requirements

### Prerequisites
- Microsoft Azure Account and subscription key for the Translator API.

### Install Dependencies
```bash
pip install requests python-docx

## Usage

### Translate Text
Use the `translator_text` function to translate a text string from English to the target language:

```python
translated_text = translator_text("Hello world!", "pt-br")
print(translated_text)

### Translate Document
Use the translator_document function to translate a .docx file and save it with the translated content:

```python
translated_path = translator_document("your_document.docx")
print(f"Translated document saved at: {translated_path}")

