# AI-story-generator
AMIN MAHJOUB SAGHAIROUN MOHAMED / 220208605
# 📚 AI Story Generator

A simple Python-based AI story generator that delivers short, creative stories from a predefined set. The user can interact with the AI to hear new stories or end the session based on their preferences.

## ✨ Features

- Generates a random story from a custom dataset (`stories.txt`)
- Interactive: responds to user feedback (like/dislike)
- Supports basic fine-tuning using Hugging Face Transformers
- Easy to run in Google Colab or local Python environment

## 🛠 How It Works

1. Load a `.txt` file containing original stories.
2. Use `datasets` to read and tokenize the stories.
3. Randomly display one story at a time and ask for feedback.
4. Optionally, fine-tune a model like `distilgpt2` for custom generation.

## 🚀 How to Run

1. Upload `stories.txt` with at least 5 stories (each 4+ lines).
2. Install dependencies in Colab:
   ```bash
   !pip install transformers datasets
