# i18next JSON Translation Tool

A simple web-based tool to translate i18next JSON resource files using the Google Cloud Translation API.

### [Live Demo](https://i18translate.asadk.dev/)

## Features

- Translate complete i18next JSON files while preserving structure
- Support for nested JSON objects
- Secure API key handling with local storage
- Copy-to-clipboard functionality
- Source and target language specification
- Error handling and validation

## Setup

1. Get a Google Cloud Translation API key:
   - Go to the [Google Cloud Console](https://console.cloud.google.com/)
   - Create a new project or select an existing one
   - Enable the Cloud Translation API
   - Create credentials (API key)
   - 

## Usage
```sh
npx http-server .
```

1. Open the HTML file in your web browser
2. Enter your Google Cloud Translation API key in the top field
3. Paste your source JSON in the left textarea
4. Specify the source language code (e.g., 'en' for English)
5. Specify the target language code (e.g., 'es' for Spanish)
6. Click the "Translate" button
7. Use the "Copy Result" button to copy the translated JSON

## Supported Language Codes

Use ISO 639-1 language codes such as:
- 'en' (English)
- 'es' (Spanish)
- 'fr' (French)
- 'de' (German)
- 'ja' (Japanese)
- etc.

## Security Note

The API key is stored locally in your browser and is only sent to Google's servers for translation requests.

## Author

Created by Asadbek Karimov
- GitHub: [asadbek064](https://github.com/asadbek064)
- Email: [contact@asadk.dev](mailto:contact@asadk.dev)
- Website: [asadk.dev](https://asadk.dev/)

## License

This project is licensed under the MIT License

---
Made with ❤️ for the i18next community

