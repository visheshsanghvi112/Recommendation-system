# Recommendation System using PySpark

This repository contains a Jupyter Notebook that demonstrates how to build a movie recommendation system using PySpark.

## Installation

To run the notebook, you need to install PySpark. You can install it using pip:

```bash
pip install pyspark
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/visheshsanghvi112/Recommendation-system.git
```

2. Navigate to the repository directory:

```bash
cd Recommendation-system
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook Recommendation-system-using-pyspark.ipynb
```

4. Run the cells in the notebook to build and evaluate the recommendation system.

## Notebook Overview

The notebook includes the following steps:

1. **Install PySpark**: Install the PySpark library.
2. **Initialize Spark Session**: Create a Spark session to work with PySpark.
3. **Load Data**: Load and preprocess the movie ratings and metadata.
4. **Data Cleaning**: Handle missing values and cast column types.
5. **Build the Model**: Use the Alternating Least Squares (ALS) algorithm to build the recommendation model.
6. **Evaluate the Model**: Evaluate the model using Root Mean Squared Error (RMSE).
7. **Make Predictions**: Generate movie recommendations for a single user.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Acknowledgments

- [PySpark Documentation](https://spark.apache.org/docs/latest/api/python/)
- [MovieLens Dataset](https://grouplens.org/datasets/movielens/)
