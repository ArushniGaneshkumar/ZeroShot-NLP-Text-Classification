# ZeroShot-NLP-Text-Classification
Transformer-based zero-shot text classification system capable of categorizing unseen text classes without task-specific training.
Overview
Implemented a transformer-based zero-shot classification framework capable of classifying text into previously unseen categories.

## Flow diagram

Rare Disease List --> Wikipedia Data Collection --> Disease Knowledge Base --> BioBERT Embedding Generation --> Disease Embedding Repository --> User Symptom Input --> BioBERT Encoding --> Cosine Similarity Matching --> Top-K Disease Prediction --> Radar/Bubble Visualization

Features
-Zero-shot inference
-Transformer-based architecture
-Domain generalization
-Flexible category definition
-No task-specific retraining

Use Cases
-News categorization
-Customer feedback analysis
-Social media monitoring
-Document classification

Tech Stack
-Python
-Transformers
-HuggingFace
-PyTorch
-Pandas
