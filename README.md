# Translation with GPT-4O

A single page web-based translation tool that utilizes OpenAI's GPT-4O model to translate text between multiple languages.

## Features

- **Automatic Language Detection**: Detects the language of the input text using GPT-4O.
- **Multiple Target Languages**: Supports translation to English, French, Spanish, German, Italian, Portuguese, Russian, Chinese, Japanese, and Arabic.
- **Dark Mode Support**: Automatically adapts to your system's theme preference and includes a toggle switch for manual control.
- **Translation History**: Saves translations locally using IndexedDB with options to view and delete entries.
- **API Key Management**: Option to save your OpenAI API key securely in the browser's local storage.

## Requirements

- **OpenAI API Key**: An API key with access to the GPT-4O model.
- **Modern Web Browser**: Supports IndexedDB and modern JavaScript features.

## Getting Started

1. **Clone or Download the Repository**

   Clone the repository or download the HTML file to your local machine.

2. **Open the HTML File**

   Open the `index.html` file in your preferred web browser.

3. **Enter Your OpenAI API Key**

   - Locate the "OpenAI API Key" input field.
   - Enter your API key.
   - *(Optional)* Check "Save API key in browser" to store your API key securely for future sessions.

4. **Input Text for Translation**

   - Paste or type the text you wish to translate into the "Original Text" textarea.
   - The language will be automatically detected and displayed next to the "Original Text" label.

5. **Select Target Language**

   - Choose your desired language from the "Target language" dropdown menu.

6. **View Translation**

   - The translation occurs automatically when you paste text, change the target language, or when the "Original Text" field loses focus.
   - The translated text appears in the "Translation" textarea.

7. **Manage Translation History**

   - Click the "History" button to view past translations.
   - Each entry shows the date, source and target languages, original text, and translated text.
   - Use the "Delete" button to remove entries from your history.

## Dark Mode Toggle

- The app respects your system's theme preference but allows manual toggling between light and dark modes.

## Notes

- Ensure your OpenAI API key has access to the GPT-4O model.
- The app uses the OpenAI Chat Completion API endpoint.
- All data, including the API key (if saved) and translation history, is stored locally in your browser.
- No data is transmitted to any server other than OpenAI's API for translation requests.

## Dependencies

- **Tailwind CSS**: Included via CDN for styling.
- **Google Fonts**: Uses "Roboto Serif" for the page title font.

## License

This project is open-source and available under the MIT License.
