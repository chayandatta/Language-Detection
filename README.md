# Language Detection

## Overview

This repository provides a language detection solution using TensorFlow for text classification. The goal is to accurately identify the language of a given text. Additionally, I am in the process of developing a FastAPI interface to make the language detection model accessible through a web interface.

## Features

- **Language Detection Model**: Utilizes TensorFlow to train a language detection model capable of accurately classifying text into different languages.
- **FastAPI Integration**: Work in progress to implement a FastAPI interface, allowing users to easily interact with the language detection model through a web-based API.
- **Scalable and Efficient**: The TensorFlow model is designed to be scalable and efficient, ensuring fast and accurate language detection even with large volumes of text.

## Repository Structure

The repository is organized as follows:

- **`model/`**: Contains scripts and notebooks used for training the language detection model using TensorFlow.
- **`core/`**: Work in progress - will contain files for integrating the model with FastAPI for web-based language detection.
- **`data/`**: Sample datasets and language resources used for training the model.
- **`requirements.txt`**: Lists all the required dependencies for running the project.

## Getting Started

1. Clone the repository:

   ```bash
   git clone git@github.com:chayandatta/Language-Detection.git
   cd Language-Detection
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Start the FastAPI development server (in progress):

   ```bash
   cd core/app
   uvicorn main:app --reload
   ```

   Access the FastAPI Swagger documentation at `http://127.0.0.1:8000/docs` for API details.

## Contributing

Contributions are welcome! If you'd like to contribute, please follow the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [GNU General Public License (GPL)](LICENSE).

Feel free to reach out with any questions or issues. Happy coding!
