Log Classification With Hybrid Classification Framework

This project implements a hybrid log classification system, combining three complementary approaches to handle varying levels of complexity in log patterns. The classification methods ensure flexibility and effectiveness in processing predictable, complex, and poorly-labeled data patterns.

Classification Approaches

1)Regular Expression (Regex):

    Handles the most simplified and predictable patterns.
    Useful for patterns that are easily captured using predefined rules.


2)Sentence Transformer + Logistic Regression:

    Manages complex patterns when there is sufficient training data.
    Utilizes embeddings generated by Sentence Transformers and applies Logistic Regression as the classification layer.


3) LLM (Large Language Models):

    Used for handling complex patterns when sufficient labeled training data is not available.
    Provides a fallback or complementary approach to the other methods.
        



Setup Instructions

1) Install Dependencies: Make sure you have Python installed on your system. Install the required   Python libraries by running the following command:   pip install -r requirements.txt


2)Run the FastAPI Server: To start the server, use the following command:uvicorn server:app --reload
