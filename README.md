# Chatbot Implementation

This repository contains a Python notebook (`chatbot.ipynb`) that implements a multi-functional chatbot with various natural language processing capabilities.

## Key Features

- **Sentiment Analysis**: Uses TextBlob to classify text sentiment as positive or negative.
- **Named Entity Recognition**: Utilizes spaCy to identify and extract named entities from input text.
- **Request Type Identification**: Determines if the user's input requests text processing, image generation, or translation.
- **Image Generation**: Simulates image generation using Hugging Face's image classification pipeline and provides captions for the generated image.
- **Translation**: Supports translation to French, Spanish, and German using Hugging Face's MarianMT model.

## Usage

1. **Run the Notebook**: Execute the cells in the `chatbot.ipynb` file.
2. **Interact with the Chatbot**: Enter text when prompted with "You:".
3. **Exit**: Type 'done' to exit the chatbot.

## Dependencies

- spaCy
- TextBlob
- Hugging Face Transformers
- torch

## Notes

- The image generation functionality is simulated and doesn't actually produce images.
- The translation feature supports French, Spanish, and German.
- The chatbot can be extended to include more features or language models as needed.

## File Structure

- `chatbot.dbc`: Databricks notebook containing the chatbot implementation.
- `chatbot.ipynb`: Python notebook containing the chatbot implementation.
- `README.md`: This file, providing an overview of the project.
