# NLP Information Retrieval Project

## Project Overview
This project aims to develop an information retrieval system that outperforms BM25 on the NFCorpus, a complex medical corpus. The system utilizes pre-treatment, vocabulary manipulation, word2vec embeddings, and BERT model embeddings for document and query understanding. Performance is evaluated using the ndcg@5 metric against a BM25 baseline.

## Setup Instructions

1. **Environment Setup**: Ensure you have Python 3.6+ installed. Create a virtual environment and activate it:

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

2. **Install Dependencies**: Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

3. **NLTK Resources**: Download necessary NLTK resources:

    ```python
    import nltk
    nltk.download('stopwords')
    nltk.download('punkt')
    ```

4. **Running the Notebook**: Open the provided Jupyter notebook (`Projet_NLP_KIOULOU_MOKHTARI.ipynb`) in a Jupyter environment or Google Colab to view the implementation details and run the project.

## Project Structure

- `requirements.txt`: Lists all the necessary Python packages.
- `Projet_NLP_KIOULOU_MOKHTARI.ipynb`: Jupyter notebook containing the project implementation.
- `README.md`: This file, containing project setup instructions and overview.

## Contributing

This project welcomes contributions and suggestions. Feel free to fork the repository and submit pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.