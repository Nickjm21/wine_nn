# Wine Quality Prediction with Neural Networks

A comprehensive machine learning project that explores wine quality prediction using various neural network architectures and traditional ML models. This project analyzes the relationship between chemical properties and wine quality ratings using the UCI Wine Quality dataset.

## Features

- **Multiple Model Types**: Linear regression, logistic regression, and neural networks
- **Data Exploration**: Comprehensive analysis of wine chemical properties
- **Visualization**: Feature distributions and model performance plots
- **Reproducible Results**: Seeded random operations for consistent outputs

## Dataset

The project uses the [Wine Quality Dataset](https://archive.ics.uci.edu/dataset/186/wine+quality) from the UCI Machine Learning Repository, containing:
- **6,497 wine samples** with 11 chemical features including acitity, ABV, etc.
- **Quality ratings** on a scale of 1-10

## Installation

### Using uv (Recommended)

```bash
# Clone the repository
git clone <repository-url>
cd wine_nn

# Install dependencies using uv
uv sync

# Activate the virtual environment
uv shell
```

### Using pip

```bash
# Clone the repository
git clone <repository-url>
cd wine_nn

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies from pyproject.toml
pip install -e .
```

## Usage

1. **Open the Jupyter notebook**:
   ```bash
   jupyter notebook main.ipynb
   ```

2. **Run the cells sequentially** to:
   - Load and explore the wine quality dataset
   - Analyze feature distributions and correlations
   - Train and compare multiple ML models
   - Visualize results and model performance

## Dependencies

- Python ≥ 3.9
- NumPy, Pandas, Matplotlib
- Scikit-learn
- PyTorch
- Jupyter Notebook
- UCI ML Repository client

## Project Structure

```
wine_nn/
├── main.ipynb          # Main analysis notebook
├── pyproject.toml      # Project configuration
├── outputs/            # Generated plots and outputs
│   └── feature_plot.png
└── README.md          # This file
```

## License

This project is open source and available under the [MIT License](LICENSE).
