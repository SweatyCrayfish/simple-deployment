# simple-deployment

### 🛡️ Badges
[![GitHub Repo stars](https://img.shields.io/github/stars/your-github-username/your-repo-name?style=social)](https://github.com/SweatyCrayfish/simple-deployment/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/SweatyCrayfish/simple-deployment/blob/main/LICENCE.md)
[![PyPi](https://img.shields.io/badge/PyPi-Page-blue)](https://pypi.org/project/simple-deployment/)
[![Downloads](https://pepy.tech/badge/simple-deployment)](https://pepy.tech/project/simple-deployment)
### 🔗 Links
- **PyPi Package**: [simple-deployment](https://pypi.org/project/simple-deployment/)

# Chatbot Interface with Flask and Hugging Face Transformers

## Description

This project is a chatbot interface that integrates Hugging Face's Transformers library with a Flask backend. It serves a frontend built with HTML, CSS, and JavaScript to interact with the user. The user can input text which is then processed by the Flask backend and fed into a pre-trained language model. The model's generated text is then sent back to the frontend and displayed.

## Folder Structure

- `frontend/`: Contains all frontend HTML, CSS, and JavaScript files.
  - `index.html`: Main HTML file that provides the user interface.
  
- `backend/`: Contains Flask application and related backend code.
  - `app.py`: Main Flask application script.
  
- `models/`: Folder where pre-trained language models are saved.
  
- `requirements.txt`: Lists all Python dependencies.

## How to Use

### Prerequisites

1. Python 3.8
2. pip
3. Flask
4. At least 6 GB RAM to host cohesive model

### Installation

1. Clone the repository.

   ```
   git clone https://github.com/SweatyCrayfish/simple-deployment/.git
   ```

2. Navigate to the project directory.

   ```
   cd simple-deploymemt
   ```

3. Install the required Python packages.

   ```
   pip install -r requirements.txt
   ```

### Running the Application

1. Start the Flask application.

   ```
   python backend/app.py
   ```

2. Open a web browser and go to `http://127.0.0.1:5000/`.

3. Use the frontend interface to interact with the chatbot. You can choose a pre-trained model from the dropdown or upload your own.

### Interacting with the Chatbot

1. Type your text into the input field and press "Send" or hit the Enter key.
2. The chatbot's response will appear below your message.

---
# Reference
Viktor Veselov 10/28/2023
