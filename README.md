# Translation Web Application

This is a web application built using Python Flask, Javascript, and HTML that provides translation functionality between English and French languages. The application leverages the IBM Watson Language Translator API for accurate and reliable translations.

## Features

- Translate text from English to French and vice versa.
- User-friendly interface for entering and displaying translated text.
- Real-time translation updates without page reloads using AJAX.

## Installation

To run this application locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/repository-name.git`
2. Navigate to the project directory: `cd repository-name`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Obtain an API key from IBM Watson Language Translator API and update the `config.py` file with your API credentials.
5. Run the application: `python server.py`
6. Open your web browser and visit `http://localhost:5000` to access the translation web application.

## Usage

- Enter the text you want to translate in the input field.
- Select the source language (English or French) and the target language.
- Click the "Translate" button to initiate the translation.
- The translated text will be displayed below the input field.
- You can continue entering new text or change the source/target languages for additional translations.

## Technologies Used

- Python Flask: Microframework for web development.
- JavaScript: Client-side scripting language for dynamic functionality.
- HTML: Markup language for creating the web page structure.
- IBM Watson Language Translator API: Language translation service for accurate and reliable translations.

## Contributions

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [Python Flask](https://flask.palletsprojects.com/)
- [IBM Watson Language Translator API](https://cloud.ibm.com/apidocs/language-translator)
- [jQuery](https://jquery.com/)

## Disclaimer

This project is for educational and demonstration purposes only. It may not provide perfect translations and should not be used for critical or sensitive translations.
