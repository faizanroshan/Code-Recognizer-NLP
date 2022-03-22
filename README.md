# Code Recognizer using NLP

## Author
[Shaik Faizan Roshan Ali](https://www.github.com/faizanroshan)
## Description
This project involves recognizing the programming language based on the code snippets. 
The dataset can be downloaded from [kaggle](https://www.kaggle.com/datasets/simiotic/github-code-snippets). The dataset used in this is a subset of the above-mentioned dataset.

## Approach
1. Import the dataset.
2. Explore the dataset.\
 (understanding the composition of different languages in the dataset)
3. Clean the dataset.\
(A few of the code snippets are not tokenizable due to their string formatting)
4. Tokenization using Doc2Vec Library.
5. Train and Export the tokenized model.
6. Build vectors for the code snippets.
7. Train and Test the model on Logistic Regression after the split.\
(Any other classification can also be implemented)

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required libraries.

## Usage
Run the notebook Code_Recognizer_Beta.ipynb in google colab or jupyter notebook.

```bash
pip install -r requirements.txt
```

## Contributing
Pull requests are welcome.

## License
[MIT](https://choosealicense.com/licenses/mit/)
