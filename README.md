# Translation with GPT-4O

A single page web-based translation tool that utilizes OpenAI's GPT-4O model to translate text between multiple languages.

## Demo

Available demo on codesandbox: https://g8mx7s-5000.csb.app/

## Features

- **Translation:** Translate text into multiple languages.
- **Model Selection:** Choose from a list of GPT models, including `gpt-4o`, `gpt-4o-mini`, `gpt-4-turbo`, `gpt-4`, and `gpt-3.5-turbo`. The model list is automatically updated to the latests available models
- **History:** View your translation history with details such as the date, target language, and model used.
- **Theme Toggle:** Switch between light and dark modes.
- **Settings:** Save your OpenAI API key and preferences in the browser.

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
  
4. **Select model**

   - Go to the settings (top right menu)
   - Select the model you want to use. Default is `gpt-4o`

5. **Input Text for Translation**

   - Paste or type the text you wish to translate into the "Original Text" textarea.
   - The language will be automatically detected and displayed next to the "Original Text" label.

6. **Select Target Language**

   - Choose your desired language from the "Target language" dropdown menu.

7. **View Translation**

   - The translation occurs automatically when you paste text, change the target language, or when the "Original Text" field loses focus.
   - The translated text appears in the "Translation" textarea.

8. **Manage Translation History**

   - Click the "History" button to view past translations.
   - Each entry shows the date, source and target languages, original text, and translated text.
   - Use the "Delete" button to remove entries from your history.

## Dark Mode Toggle

- The app respects your system's theme preference but allows manual toggling between light and dark modes.

## Models

The application allows you to select from the following GPT models:

- `gpt-4o` (default)
- `gpt-4o-mini`
- `gpt-4-turbo`
- `gpt-4`
- `gpt-3.5-turbo`

At first load, the app will load all the recent models available.

## Notes

- Ensure your OpenAI API key has access to the GPT-4O model.
- The app uses the OpenAI Chat Completion API endpoint.
- All data, including the API key (if saved) and translation history, is stored locally in your browser.
- No data is transmitted to any server other than OpenAI's API for translation requests.

## Dependencies

- **Tailwind CSS**: Included via CDN for styling.
- **Google Fonts**: Uses "Roboto Serif" for the page title font.

## License

Code generated through GPT-4o1
This project is open-source and available under the MIT License.
