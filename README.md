# Face Recognition Using Eigenfaces

This repository contains the implementation of a Face Recognition system using the Eigenfaces algorithm. The project demonstrates the application of Principal Component Analysis (PCA) for dimensionality reduction and feature extraction in the domain of computer vision.

## Project Structure

- `eigen_ipynb.ipynb`: Jupyter notebook with the full implementation and documentation of the Eigenfaces algorithm.
- `crop.zip`: Zipped dataset containing cropped images for training the model.
- `test.zip`: Zipped dataset containing test images to evaluate the model's performance.

## Getting Started

To get started with this project, clone the repository and install the required dependencies listed in `requirements.txt` (if provided).

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries: numpy, matplotlib, scikit-learn (install these using `pip` or `conda`)

### Installation

1. Clone the repository: `git clone https://github.com/ksheersagaragrawal/Face-Recognition-Using-Eigenfaces.git`
2. Navigate to the cloned directory and install dependencies (if `requirements.txt` is available): `pip install -r requirements.txt`
3. Unzip the datasets: `unzip crop.zip -d path_to_extract/` `unzip test.zip -d path_to_extract/`


## Usage

Run the Jupyter notebook to see the step-by-step process of the Eigenfaces algorithm: `jupyter notebook eigen_ipynb.ipynb`

Follow the instructions within the notebook to train and test the Face Recognition model.

## Results

The `eigen_ipynb.ipynb` notebook contains visualizations and performance metrics demonstrating the efficacy of the Eigenfaces algorithm in recognizing faces.

## Contributing

Contributions to this project are welcome. Please read `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Acknowledgments

- The dataset used in this project is a subset of the [Labeled Faces in the Wild](http://vis-www.cs.umass.edu/lfw/) dataset.
- Thanks to all contributors who have participated in this project.
