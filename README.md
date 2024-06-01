# Transformers for Language Modeling

## Introduction

In this project, I implement a Transformer model, `SastaGPT`, from scratch, based on the paper [Attention Is All You Need](https://arxiv.org/abs/1706.03762) by Vaswani et al. (2017). The model is trained on a language modeling task using a dataset composed of selected poems by Edgar Allan Poe.

## Table of Contents

- [Installation](#installation)
- [Dataset Preparation](#dataset-preparation)
- [Model Implementation](#model-implementation)
- [Training the Model](#training-the-model)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this project, you will need Python and several Python libraries. You can install the necessary dependencies using pip:

```bash
pip install numpy pandas matplotlib torch tiktoken
```

## Dataset Preparation

The dataset used for training the Transformer model consists of selected poems by Edgar Allan Poe. You can replace this dataset with any text dataset of your choice. Some fun options include:

- A collection of movie scripts from your favorite director. You can find some options on [IMSDB](https://www.imsdb.com/).
- A novel from your favorite author, available on [Project Gutenberg](https://www.gutenberg.org/).

## Model Implementation

The model implementation includes the following key components:

1. **Positional Encoding**: Adds information about the position of each token in the sequence.
2. **Multi-Head Attention**: Allows the model to focus on different parts of the input sequence simultaneously.
3. **Feed-Forward Network**: Applies non-linear transformations to the input.
4. **Layer Normalization**: Normalizes the inputs to each sub-layer.
5. **Encoder and Decoder Stacks**: Consists of multiple layers of the above components.

## Training the Model

To train the model, follow these steps:

1. **Load the Dataset**: Ensure your dataset is properly formatted and loaded into the script.
2. **Preprocess the Data**: Tokenize the text data using a tokenizer (e.g., `tiktoken`).
3. **Initialize the Model**: Define the model architecture and initialize it.
4. **Train the Model**: Set up the training loop, loss function, and optimizer. Train the model on your dataset.

## Evaluation

After training the model, evaluate its performance on a validation or test dataset. You can use metrics such as perplexity or other relevant metrics for language modeling tasks.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

For any further questions, feel free to reach out to me at 25100325@lums.edu.pk
