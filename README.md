# llamaChatAgent-withSentimentAnalysis

https://colab.research.google.com/drive/1ryDPe4SUmJnCtsSpq6n192pJ7o4mG8ze?usp=sharing

This project enhances the functionality of a Llama 2 chatbot by integrating sentiment analysis to create an emotionally intelligent Mental Health Assistant. The chatbot analyzes user inputs using Hugging Face's distilbert-base-uncased-finetuned-sst-2-english sentiment analysis model to detect positive, negative, or neutral emotions. Depending on the sentiment detected, the chatbot adjusts its responses to offer appropriate emotional support. For instance, when negative sentiments are detected, the chatbot picks up on it then generates the main response using the Llama 2 model.

This project leverages Hugging Face Transformers, Gradio for the user interface, and Google Colab for development, demonstrating the potential of AI in mental health applications.

