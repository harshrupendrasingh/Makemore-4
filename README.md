# MLP: Character-Level Language Model
This repository contains a minimalist implementation of a Multilayer Perceptron (MLP) for character-level sequence generation, built entirely from scratch without relying on high-level frameworks for training.

The project focuses on learning the internals of neural networks, including:

Manual backpropagation
Batch normalization
Character embeddings
Training optimization from first principles
Features
No prebuilt training functions: Forward and backward passes are written from scratch.
Batch Normalization: Implemented manually to stabilize training.
Manual Backpropagation: Deep dive into gradient computation and optimization.
Text Generation: Trained on a names dataset, the model generates names character-by-character.
Learning Outcomes
This project deepens understanding of:

Neural network mechanics (forward pass, gradients).
Training techniques like batch normalization.
Practical implementation inspired by foundational research papers.
Dataset
The model trains on a dataset of names stored in names.txt. Each name is tokenized character-by-character, including start and stop tokens.

Usage
Clone this repository:
bash
Copy code
git clone https://github.com/yourusername/mlp-char-model.git  
cd mlp-char-model  
Ensure names.txt is in the root folder.
Run the training script:
bash
Copy code
python train.py  
Generate names:
bash
Copy code
python generate.py  
Research Inspiration
This project is inspired by foundational papers like:

Efficient Estimation of Word Representations in Vector Space
Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift
Dependencies
Python
PyTorch
Contributing
Contributions to improve training, add features, or optimize the implementation are welcome. Feel free to open issues or pull requests.

License
This project is licensed under the MIT License.

Explore, learn, and enjoy building neural networks from the ground up! 🚀
