# Time SeriesTools: A Collection of Python Frameworks for Time Series Analysis

The TimeSeriesTools repository provides a comprehensive collection of Python frameworks and libraries for analyzing and processing time series data. Whether you're working with financial data, sensor readings, or any other type of time-stamped data, this repository offers a wide range of tools to help you extract insights and gain valuable insights.


## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Content](#content)
  - [Python Frameworks for Time Series Analysis](#python-frameworks-for-time-series-analysis)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Time series analysis is a critical aspect of data science and analytics, enabling businesses and researchers to uncover patterns and trends over time. This repository aims to consolidate the best Python libraries for time series analysis, making it easier for developers and analysts to find the tools they need.

## Installation

To use these libraries, you need Python installed on your system. You can set up a virtual environment and install the libraries using `pip` or `conda`. Here's a quick start guide:

```bash
# Create and activate a virtual environment
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

# Install the libraries (example for a couple of them)
pip install pandas statsmodels prophet tsfresh sktime darts pyflux gluonts pycaret tensorflow aeon pyts tsfeatures
```


# Content

## Python Frameworks for Time Series Analysis

1. [Pandas](https://pandas.pydata.org/) A powerful, fast, flexible, and easy-to-use open-source data analysis and manipulation library for Python. It provides data structures like Series and DataFrames, which are essential for time series data manipulation. [Pandas docs](https://pandas.pydata.org/pandas-docs/stable/)

2. [Statsmodels](https://www.statsmodels.org/stable/index.html): Library for statistical modeling in Python. It provides classes and functions for the estimation of many different statistical models, as well as for conducting statistical tests and statistical data exploration. Statsmodels offers powerful tools for time series analysis, including ARIMA, SARIMAX, and VAR models. [Statsmodels docs](https://www.statsmodels.org/stable/index.html)

3. [Prophet](https://facebook.github.io/prophet/) An open-source tool developed by Facebook for producing high-quality forecasts for time series data that have daily observations with patterns on different time scales (daily, weekly, yearly) and holidays. It is particularly good at handling missing data and shifts in the trend. [Prophet docs](https://facebook.github.io/prophet/docs/quick_start.html)

4. [tsfresh](https://tsfresh.readthedocs.io/en/latest/) Python library for automatic extraction of relevant features from time series data. It computes a large number of features for each time series and then selects the most useful ones to describe the data effectively, allowing for improved model accuracy. [tsfresh docs](https://tsfresh.readthedocs.io/en/latest/)

5. [Sktime](https://www.sktime.org/): A unified framework for machine learning with time series. It provides tools for time series classification, regression, forecasting, and annotation, offering an interface to various time series models and methods. [Sktime docs](https://www.sktime.net/en/stable/)


6. [Darts](https://github.com/unit8co/darts): Python library for easy manipulation and forecasting of time series. It offers a variety of models, from ARIMA to deep learning-based models like N-BEATS, and provides a unified interface to work with different models seamlessly. [Darts docs](https://github.com/unit8co/darts)

7. [PyFlux](https://pyflux.com/): library for time series analysis and forecasting. It supports Bayesian inference methods and provides tools for working with state space models, time series decomposition, and other statistical techniques. [PyFlux docs](https://pyflux.readthedocs.io/en/latest/)

8. [GluonTS](https://github.com/awslabs/gluon-ts): Python library for probabilistic time series modeling, built on Apache MXNet. It provides models such as DeepAR, DeepState, and other cutting-edge time series forecasting models that can handle uncertainty in predictions. [GluonTS docs](https://gluon-ts.mxnet.io/)

9. [PyCaret](https://pycaret.gitbook.io/docs/) PyCaret is an open-source, low-code machine learning library in Python that automates the entire machine learning pipeline. It supports time series analysis with modules for data preparation, feature engineering, and model training. [PyCaret docs](https://pycaret.gitbook.io/docs/)

10. [TensorFlow Time Series](https://www.tensorflow.org/tutorials/structured_data/time_series) TensorFlow Time Series provides capabilities to create, train, and evaluate time series models. It supports various neural network architectures designed for time series prediction. [TensorFlow Time Series docs](https://www.tensorflow.org/tutorials/structured_data/time_series)

11. [AEON](https://github.com/aeon-toolkit/aeon): Python library designed to unify various time series machine learning tasks. It provides a suite of tools for time series classification, regression, and forecasting. AEON offers a consistent API to handle time series data across different models and tasks. [AEON docs](https://www.aeon-toolkit.org/)

12. [PyTS](https://github.com/johannfaouzi/pyts): Python package for time series classification. It provides various algorithms and utilities specifically tailored for time series classification tasks, including transformation techniques and machine learning algorithms. [PyTS docs](https://pyts.readthedocs.io/en/stable/)

13. [tsfeatures](https://github.com/Nixtla/tsfeatures): Python implementation of the R package for time series feature extraction. It calculates a wide range of features from time series data, including autocorrelations, spectral entropy, seasonality, and trend measures. Users can also define their custom feature extraction functions. [tsfeatures docs](https://pkg.robjhyndman.com/tsfeatures/)


## Contributing

Contributions are welcome! If you have any additional libraries to add, or if you find a bug or have an idea for improvement, please feel free to open an issue or submit a pull request. Follow the [contribution guidelines](CONTRIBUTING.md) for more details.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
