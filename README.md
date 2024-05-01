# DA623: Computing with Signals

## Tutorial Creation

This repository is dedicated to the practical application and comparison of three fundamental signal processing and vector transformation techniques: PCA (Principal Component Analysis), Gram-Schmidt orthogonalization, and DFT (Discrete Fourier Transform). The project demonstrates these methods using a dataset of random Gaussian vectors, each with 128 dimensions, to showcase their respective impacts and results.

## Project Structure

- `Tutorial.ipynb`: The Jupyter notebook that contains the implementations and visualizations of PCA, Gram-Schmidt, and DFT.
- `requirements.txt`: A file listing all the necessary Python libraries required to run the project, including NumPy and SciPy.
- `README.md`: This file, providing an overview and instructions for setting up and running the project.

## Installation

To run this project, you will need Python and several Python libraries, including NumPy, SciPy, and Matplotlib. You can install all required libraries using the following command:

```bash
pip install -r requirements.txt
```

## Visualizations

The notebook will produce three plots:

1. **PCA Plot**: Shows the data projected onto the first two principal components.
2. **Gram-Schmidt Plot**: Displays the orthogonal vectors obtained from the original dataset.
3. **DFT Plot**: Illustrates the magnitude spectrum of the vectors, indicating frequency components.

## License

This project is available under the MIT License. For more details, see the `LICENSE` file in this repository.
