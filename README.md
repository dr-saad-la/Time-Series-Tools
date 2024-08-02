# Time SeriesTools: A Collection of Python Frameworks for Time Series Analysis

The Time-Series-Tools repository provides a comprehensive collection of Python, Julia, R, Java, Rust and Cplusplus frameworks and libraries for analyzing and processing time series data. 

The objective of this repository is to help researchers, data scientists, data analysts, students of hobyists who are working with time series data such as financial data, sensor readings, or any other type of time-stamped data, to find and access the appropriate library for framework in different programming languages. 

The reason for selecting this set of programming languages is the familiary of the author and mantainer of this repo, however, other programming languages might be added in the future.


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


## Julia Packages for Time Series Analysis

1. [TimeSeries.jl](https://github.com/JuliaStats/TimeSeries.jl) This library provides a framework for working with time series data in Julia. It includes convenient methods for manipulating and analyzing time series data using the `TimeArray` data structure, which is similar to pandas Series. [TimeSeries.jl docs](https://juliastats.org/TimeSeries.jl/latest/)

2. [TSAnalysis.jl](https://github.com/fipelle/TSAnalysis.jl): It offers tools for basic time series analysis in Julia. It is compatible with incomplete data and includes state-space modeling capabilities. The package provides functions for estimation and validation of time series models. [TSAnalysis.jl docs](https://juliapackages.com/p/tsanalysis)

3. [StateSpaceModels.jl](https://github.com/LAMPSPUC/StateSpaceModels.jl) It is designed for time-series analysis using state-space models. It includes functionalities like the Kalman filter, maximum likelihood estimation, and various predefined models such as SARIMA, exponential smoothing, and unobserved components models. [StateSpaceModels.jl docs](https://juliapackages.com/p/statespacemodels)

4. [Temporal.jl](https://github.com/dysonance/Temporal.jl) It provides a flexible time series class, `TS`, for handling and analyzing time series data in Julia. It aims to offer rapid prototyping capabilities similar to R's xts and Python's pandas, while leveraging Julia's performance benefits. [Temporal.jl docs](https://github.com/dysonance/Temporal.jl)

5. [OnlineStats.jl](https://github.com/joshday/OnlineStats.jl) It offers algorithms for real-time statistics and machine learning, particularly useful for time series data. It includes techniques for computing moving averages, control charts, and echo state networks, making it ideal for streaming data analysis. [OnlineStats.jl docs](https://joshday.github.io/OnlineStats.jl/stable/)

6. [DynamicalSystems.jl](https://github.com/JuliaDynamics/DynamicalSystems.jl) It is a comprehensive library for analyzing nonlinear dynamical systems and chaos. It provides tools for timeseries analysis, including Lyapunov exponents, attractor reconstruction, and other nonlinear dynamics techniques. [DynamicalSystems.jl docs](https://juliadynamics.github.io/DynamicalSystems.jl/latest/)

7. [ARCHModels.jl](https://github.com/s-broda/ARCHModels.jl) It implements ARMA-GARCH models for time series analysis in Julia. It supports estimation, forecasting, and diagnostics of volatility models, providing a robust framework for financial time series analysis. [ARCHModels.jl docs](https://s-broda.github.io/ARCHModels.jl/stable/)

8. [MessyTimeSeries.jl](https://github.com/fipelle/MessyTimeSeries.jl) It is geared towards handling time series data that may have missing or messy components. It provides tools for estimation and modeling, helping users clean and analyze imperfect data sets. [MessyTimeSeries.jl docs](https://github.com/fipelle/MessyTimeSeries.jl)

9. [ChaosTools.jl](https://github.com/JuliaDynamics/ChaosTools.jl)
   Part of the DynamicalSystems.jl ecosystem, ChaosTools.jl focuses on the analysis of chaos in time series data. It offers functionalities for chaos detection and quantification, including phase space reconstruction and bifurcation analysis. [ChaosTools.jl docs](https://juliadynamics.github.io/DynamicalSystems.jl/dev/chaos/)

10. [Econometrics.jl](https://github.com/Nosferican/Econometrics.jl) It provides econometric models and methods for analyzing time series data. It includes implementations for autoregressive models, vector autoregressions, and cointegration techniques, making it suitable for economic and financial data analysis. [Econometrics.jl docs](https://nosferican.github.io/Econometrics.jl/stable/)

## Contributing

Contributions are welcome! If you have any additional libraries to add, or if you find a bug or have an idea for improvement, please feel free to open an issue or submit a pull request. Follow the [contribution guidelines](CONTRIBUTING.md) for more details.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

