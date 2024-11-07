# **Translator Application**

This project is a Translator application built using Python with the Tkinter GUI toolkit and the `googletrans` library for translation functionality. It provides a user-friendly interface for translating text between multiple languages, making it a handy tool for anyone needing quick translations.

## **Features**

- **Language Selection**: Choose source and target languages from a dropdown list of supported languages.
- **Text Translation**: Enter text in the source language field and click "Translate" to get the translated text in the target language field.
- **Custom Error Handling**: Displays custom error messages for any issues during translation.

## **Prerequisites**

- Python 3.x
- `googletrans` library for language translation:
  
    ```bash
    pip install googletrans==4.0.0-rc1
    ```

## **Getting Started**

1. **Clone the Repository**:

    ```bash
    git clone <your-repository-url>
    ```

2. **Run the Application**:

    ```bash
    python translator.py
    ```

## **Usage**

- **Select Languages**: Use the dropdown menus to select the source and target languages.
- **Input Text**: Type or paste text in the left text box.
- **Translate**: Click the "Translate" button to display the translated text in the right text box.

## **Code Overview**

- **GUI Elements**:
  - The main GUI includes two dropdown menus for selecting languages, text boxes for input and output, and a "Translate" button for executing translations.
  - Custom error messages are displayed using a pop-up box in case of any issues.

- **Translation Logic**:
  - Uses `googletrans`'s `Translator` class to perform translations.
  - The `translate_now` function handles translation and updates the output text box with the translated text.

## **License**

This project is licensed under the MIT License. Feel free to modify and use it for your own purposes.
