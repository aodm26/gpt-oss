Project Overview: Financial News Sentiment Engine

This system implements a high-throughput inference pipeline using PyTorch and Hugging Face Transformers to process financial data. It uses a structured prompt engineering approach to extract concise reasoning and sentiment labels from raw text.
Core Functionalities

    Structured Prompt Engineering: Employs a rigorous system prompt that forces the model to output reasoning (under 10 words) and a sentiment label, ensuring machine-parseable results.

    Batched Inference Pipeline: Implements a batch-processing loop (BatchSize=8) with GPU acceleration to optimize throughput and handle large datasets efficiently.

    Comprehensive Evaluation Suite: Uses scikit-learn and Seaborn to generate Confusion Matrices, accuracy scores, and detailed classification reports (Precision, Recall, F1-Score).

    Error Analysis & Debugging: Features a dedicated misclassification tracker that logs "Predicted vs. Expected" labels and the model’s reasoning to identify patterns in edge cases.

Technical Stack

    Languages & Frameworks: Python, PyTorch, Hugging Face (Transformers/Tokenizers).

    Data Science: Pandas for result management, Matplotlib/Seaborn for visualization.

    AI Techniques: LLM Generation, Prompt Optimization, and Tokenization handling
