# Sentiment Analysis Chatbot

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Overview
This project implements a **Sentiment Analysis Chatbot** using a **pre-trained BERT model**. The chatbot analyzes user input and classifies it into one of five sentiment categories:

1. Very Negative
2. Negative
3. Neutral
4. Positive
5. Very Positive

Based on the sentiment, the chatbot generates an appropriate response to continue the conversation naturally.

---

## Project Structure
```plaintext
.
├── data/                  # Data storage (if needed)
├── models/                # Trained models (if any)
├── sentiment_chatbot.py    # Main chatbot script
├── requirements.txt        # Dependencies required to run the project
├── README.md               # Project README file
└── LICENSE                 # Project License
```

---

## Features

- **BERT-based Sentiment Analysis**: Uses a pre-trained `nlptown/bert-base-multilingual-uncased-sentiment` model.
- **Dynamic Responses**: Generates chatbot responses based on the detected sentiment.
- **Interactive Chatbot**: Continuously engages in conversation until the user exits.
- **Multi-class Sentiment Detection**: Detects five levels of sentiment (Very Negative to Very Positive).
- **User-Friendly CLI Interface**: Simple and interactive terminal-based chatbot.

---

## Technologies Used

- **Python**: Core programming language.
- **PyTorch**: Used for loading and running the BERT model.
- **Transformers (Hugging Face)**: Provides the BERT tokenizer and model.
- **NLTK**: Used for loading the movie reviews dataset.
- **Random**: Generates varied responses for a more human-like conversation.

---

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```sh
   git clone https://github.com/mohit0825/Sentiment-Analysis-Chatbot.git
   ```

2. **Navigate into the project directory:**
   ```sh
   cd Sentiment-Analysis-Chatbot
   ```

3. **Install the required dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

---

## Usage

To run the chatbot, simply execute:

```sh
python sentiment_chatbot.py
```

- Type your message and the chatbot will analyze the sentiment.
- The chatbot will respond accordingly.
- Type **'quit'** to exit the chatbot.

---

## How It Works

1. **User Input:** The chatbot takes a text input from the user.
2. **Sentiment Prediction:**
   - The input is tokenized using the BERT tokenizer.
   - The BERT model predicts the sentiment category (0-4).
   - The output is converted into a readable sentiment label.
3. **Response Generation:**
   - The chatbot selects a predefined response based on the detected sentiment.
   - The response is printed to the console.

---

## Results

The chatbot effectively classifies text sentiment and provides appropriate responses. The BERT model enables it to handle diverse inputs with reasonable accuracy.

---

## Contributing

Contributions are welcome! If you’d like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new feature branch:
   ```sh
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```sh
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```sh
   git push origin feature-branch
   ```
5. Create a new Pull Request.

---

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

## Contact

For any questions or suggestions, please contact:

•	Ayush Raj
	•	Email: ar5787@srmist.edu.in
	•	GitHub: Ayushomega14

