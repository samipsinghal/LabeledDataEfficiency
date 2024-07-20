# Labeled Data Efficiency with GCN and FNN

This repository contains the implementation of a project focusing on improving labeled data efficiency using Graph Convolutional Networks (GCN) and Feedforward Neural Networks (FNN).

## Overview

The goal of this project is to achieve accurate predictions with limited labeled data by leveraging the power of Graph Convolutional Networks (GCN) and Feedforward Neural Networks (FNN). The notebook includes steps to preprocess the data, implement the GCN and FNN models, and evaluate their performance. The results demonstrate how these models can effectively handle tasks with limited labeled data.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Examples](#examples)
- [References](#references)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run the notebook and reproduce the results, you need to have Python and the necessary libraries installed. Follow the steps below to set up your environment:

1. Clone the repository:
    ```sh
    git clone https://github.com/samipsinghal/LabeledDataEfficiency.git
    cd LabeledDataEfficiency
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

To use this repository, open the `GCN_FNN.ipynb` notebook in Jupyter Notebook or Jupyter Lab. You can run the cells in the notebook to understand the steps involved in the implementation of GCN and FNN models and see the results of various experiments.

## Project Structure

The repository is structured as follows:

- `GCN_FNN.ipynb`: Main Jupyter Notebook containing the project implementation.
- `requirements.txt`: List of Python libraries required to run the notebook.

## Examples

Here are some of the key sections covered in the main notebook (`GCN_FNN.ipynb`):

1. **Introduction to GCN and FNN**: Overview of Graph Convolutional Networks and Feedforward Neural Networks, their importance, and applications.
2. **Data Preparation**: Steps to preprocess the data for training the GCN and FNN models.
3. **Algorithm Implementation**: Detailed implementation of the GCN and FNN models.
4. **Training and Evaluation**: Training the GCN and FNN models on the dataset and evaluating their performance.
5. **Results and Analysis**: Visualization and analysis of the results obtained from the experiments. The results demonstrate how GCN and FNN can effectively handle tasks with limited labeled data, improving labeled data efficiency.

## References

1. T. Kipf and M. Welling, Semi-Supervised Classification with Graph Convolutional Networks (2017). arXiv preprint arXiv:1609.02907. ICLR 2017
2. [LINQS Data](https://linqs.soe.ucsc.edu/data)
3. D. Grattarola and C. Alippi, Graph Neural Networks in TensorFlow and Keras with Spektral (2020). arXiv:2006.12138. ICML 2020 - GRL+ Workshop
4. [https://arxiv.org/abs/1706.02216](https://arxiv.org/abs/1706.02216)
5. [Spektral: Streamlining Graph Convolution Networks](https://medium.com/swlh/spektral-streamlining-graph-convolution-networks-111ce5045c83)
6. [https://arxiv.org/abs/2006.12138](https://arxiv.org/abs/2006.12138)
7. [Spektral GitHub - Node Prediction](https://github.com/danielegrattarola/spektral/blob/master/examples/node_prediction/citation_gcn.py)
8. [Graph Neural Networks](https://graphneural.network/)
9. [The AI Summer - Graph Convolutional Networks](https://theaisummer.com/graph-convolutional-networks/)

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to create a pull request or open an issue.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
