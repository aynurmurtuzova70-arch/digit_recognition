# MNIST Digit Recognition

This project contains a Jupyter notebook that explores the classic MNIST handwritten digit dataset and builds a simple machine learning model to classify whether an image is the digit `5`.

## Project overview

The notebook demonstrates:

- loading the MNIST dataset from `scikit-learn`
- inspecting the dataset structure and sample images
- splitting the data into training and test sets
- creating a binary classifier for the digit `5`
- evaluating model performance with cross-validation and accuracy scoring
- comparing against a dummy baseline classifier

## Files

- `mnist_digit_recognition.ipynb` — the main notebook containing the data loading, preprocessing, and model evaluation steps

## Requirements

To run the notebook, install the following Python packages:

```bash
pip install numpy pandas scikit-learn matplotlib jupyter
```

## Run it locally

1. Open the project folder.
2. Start Jupyter Notebook or Jupyter Lab:

```bash
jupyter notebook
```

3. Open `mnist_digit_recognition.ipynb`.
4. Run the cells in order.

## What the notebook does

The workflow is based on the standard `fetch_openml` MNIST dataset loader and uses `SGDClassifier` from `scikit-learn` to perform binary classification. The notebook focuses on detecting the digit `5`, with training and test splits created from the full dataset.

It also shows:

- image visualization using `matplotlib`
- label extraction for the target class
- model scoring and validation metrics
- comparison with a naive baseline

## Notes

- The dataset is fetched from OpenML using the MNIST dataset ID `554`.
- This notebook is a learning/demo project and is intentionally simple rather than production-ready.

## License

This project is provided for educational and experimental use.
