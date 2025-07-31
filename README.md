# News-Summarizer-with-T5

This project fine-tunes a T5-small model for abstractive text summarization of news articles.
It generates concise and meaningful headlines from long news descriptions, showcasing transformer-based sequence-to-sequence learning.

# Methodology
Preprocessing: Cleaned text with NLTK; tokenized inputs and headlines using Hugging Face T5Tokenizer.
Model: Fine-tuned T5-small for seq2seq summarization.
Training: 1 epoch with Seq2SeqTrainer evaluated using ROUGE metrics.
Evaluation: Achieved strong ROUGE scores, validating summary quality.

# RESULTS
Generated accurate and contextually relevant headlines for news descriptions.
ROUGE metrics confirmed quality of generated summaries.
