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


## R Packages for Time Series Analysis

1. [forecast](https://cran.r-project.org/web/packages/forecast/index.html) This package is one of the most widely used packages for time series forecasting in R. It includes functions for automatic ARIMA modeling, exponential smoothing (ETS), and many other forecasting techniques. The package also offers tools for visualizing and evaluating forecast accuracy. [forecast docs](https://otexts.com/fpp3/)

2. [xts](https://cran.r-project.org/web/packages/xts/index.html) The `xts` package provides an extensible time series class that enables fast and flexible manipulation of time series data. It is built on top of the `zoo` package and integrates well with financial data and other time-indexed data structures. [xts docs](https://cran.r-project.org/web/packages/xts/xts.pdf)

3. [zoo](https://cran.r-project.org/web/packages/zoo/index.html) The `zoo` package provides an S3 class for indexed totally ordered observations, with a focus on irregular time series data. It offers efficient tools for data manipulation, analysis, and visualization, supporting arbitrary R data types. [zoo docs](https://cran.r-project.org/web/packages/zoo/zoo.pdf)

4. [tsibble](https://cran.r-project.org/web/packages/tsibble/index.html) The `tsibble` package provides a tidy data framework specifically designed for time series data in R. It simplifies time series manipulation and modeling, and it integrates seamlessly with the tidyverse suite of packages. [tsibble docs](https://tsibble.tidyverts.org/index.html)

5. [fable](https://cran.r-project.org/web/packages/fable/index.html) The `fable` package is a modern framework for time series forecasting in R, built on top of `tsibble`. It provides a wide array of forecasting models, including ARIMA, ETS, and prophet, and offers tools for model evaluation and comparison. [fable docs](https://fable.tidyverts.org/)

6. [TSA](https://cran.r-project.org/web/packages/TSA/index.html) The `TSA` package provides a variety of tools for time series analysis, including methods for ARIMA, spectral analysis, and seasonal decomposition. It is widely used for educational purposes and practical time series applications. [TSA docs](https://cran.r-project.org/web/packages/TSA/TSA.pdf)

7. [tseries](https://cran.r-project.org/web/packages/tseries/index.html) The `tseries` package includes a collection of tools for time series analysis and computational finance. It provides functions for unit root tests, ARIMA modeling, and GARCH models, among others. [tseries docs](https://cran.r-project.org/web/packages/tseries/tseries.pdf)

8. [prophet](https://cran.r-project.org/web/packages/prophet/index.html) Developed by Facebook, `prophet` is a forecasting tool designed for time series data with daily observations. It handles missing data and holiday effects well, and it is particularly useful for business forecasting. [prophet docs](https://facebook.github.io/prophet/docs/quick_start.html)

9. [seasonal](https://cran.r-project.org/web/packages/seasonal/index.html) The `seasonal` package provides interfaces to the X-13ARIMA-SEATS seasonal adjustment method developed by the US Census Bureau. It is used for seasonal decomposition of time series data and includes many utilities for customization and visualization. [seasonal docs](https://cran.r-project.org/web/packages/seasonal/vignettes/seas.html)

10. [quantmod](https://cran.r-project.org/web/packages/quantmod/index.html) The `quantmod` package is designed for quantitative financial modeling and trading in R. It provides tools for modeling, technical analysis, and charting, and it integrates well with time series data for financial applications. [quantmod docs](https://cran.r-project.org/web/packages/quantmod/quantmod.pdf)

11. [timeSeries](https://cran.r-project.org/web/packages/timeSeries/index.html)The `timeSeries` package offers S4 classes for financial time series data, providing a comprehensive framework for data manipulation, analysis, and visualization in R. It supports various financial data formats and offers many utilities for handling time series. [timeSeries docs](https://cran.r-project.org/web/packages/timeSeries/timeSeries.pdf)

12. [tsDyn](https://cran.r-project.org/web/packages/tsDyn/index.html) The `tsDyn` package provides tools for nonlinear time series models, including threshold autoregressive models and neural network models. It is particularly useful for modeling complex dynamics in time series data. [tsDyn docs](https://cran.r-project.org/web/packages/tsDyn/tsDyn.pdf)

13. [KFAS](https://cran.r-project.org/web/packages/KFAS/index.html) The `KFAS` package provides tools for state-space modeling and time series analysis using the Kalman filter. It supports various types of models, including dynamic regression and ARIMA models, and provides utilities for forecasting and model diagnostics. [KFAS docs](https://cran.r-project.org/web/packages/KFAS/KFAS.pdf)

14. [vars](https://cran.r-project.org/web/packages/vars/index.html) The `vars` package implements vector autoregressive models, vector error correction models, and structural vector autoregressive models. It is widely used for multivariate time series analysis in R. [vars docs](https://cran.r-project.org/web/packages/vars/vars.pdf)

15. [imputeTS](https://cran.r-project.org/web/packages/imputeTS/index.html) The `imputeTS` package provides tools for time series missing value imputation. It includes various methods, such as mean imputation, Kalman smoothing, and seasonally decomposed missing value imputation, making it ideal for preprocessing incomplete datasets. [imputeTS docs](https://cran.r-project.org/web/packages/imputeTS/imputeTS.pdf)


## Java Libraries for Time Series Analysis


1. **[JFreeChart](https://github.com/jfree/jfreechart)** A comprehensive charting library that supports a wide range of chart types, including time series plots. It is widely used for visualizing time series data in Java applications and offers flexible options for customization. [JFreeChart docs](https://www.jfree.org/jfreechart/api/javadoc/)

2. [JTimeSeries](http://jtimeseries.sourceforge.net/) JTimeSeries is a library for storing and manipulating time series data. It provides support for data aggregation, transformation, and querying. The library also offers utilities for working with real-time data and historical analysis. [JTimeSeries docs](http://jtimeseries.sourceforge.net/docs/index.html)

3. **[Apache Commons Math](https://commons.apache.org/proper/commons-math/)**Apache Commons Math is a library of mathematical and statistical components, including utilities for time series analysis. It provides implementations of autoregressive models, moving averages, and other time series techniques. [Commons Math docs](https://commons.apache.org/proper/commons-math/javadocs/api-3.6.1/)

4. **[Time4J](https://github.com/MenoData/Time4J)** Time4J is an advanced date and time library for Java that supports time series data manipulation. It offers a wide range of features for handling complex time calculations, calendar systems, and temporal queries. [Time4J docs](https://time4j.net/)

5. **[Deeplearning4j (DL4J)](https://deeplearning4j.konduit.ai/)** Deeplearning4j is a deep learning library for Java that offers tools for time series forecasting and anomaly detection. It supports recurrent neural networks (RNNs) and long short-term memory (LSTM) networks, making it suitable for complex time series tasks. [Deeplearning4j docs](https://deeplearning4j.konduit.ai/)

6. **[Tetrad](https://github.com/cmu-phil/tetrad)** Tetrad is a suite of tools for causal discovery and statistical modeling, including time series analysis. It provides methods for structure learning, causal inference, and graphical modeling of time series data. [Tetrad docs](https://cmu-phil.github.io/tetrad/)

7. **[FMI4j](https://github.com/CATIA-Systems/FMI4j)** FMI4j is a Java library for interfacing with Functional Mock-up Units (FMUs), which can include time series data. It allows integration of time series simulations with other model-based systems. [FMI4j GitHub](https://github.com/CATIA-Systems/FMI4j)

7. **[OpenForecast](https://sourceforge.net/projects/openforecast/)**OpenForecast is a Java library for forecasting and modeling time series data. It supports various forecasting methods, including moving averages, exponential smoothing, and linear regression. [OpenForecast docs](https://sourceforge.net/projects/openforecast/)

8. [JMARS](https://jmars.mars.asu.edu/) JMARS (Java Mission-planning and Analysis for Remote Sensing) is a software suite developed by Arizona State University for visualizing and analyzing planetary data. It includes tools for time series analysis, particularly for planetary and astronomical datasets. [JMARS docs](https://jmars.mars.asu.edu/manual/)


9. [JOptics](https://sourceforge.net/projects/joptics/) JOptics is a library for clustering and analysis of spatial and temporal data. It implements the OPTICS (Ordering Points to Identify the Clustering Structure) algorithm, which can be used for time series clustering and outlier detection. [JOptics docs](https://sourceforge.net/projects/joptics/files/Documentation/)

11. [M4 Forecasting Competition](https://github.com/M4Competition/M4-methods) The M4 Forecasting Competition repository includes Java implementations of various forecasting methods used in the competition. It provides access to state-of-the-art forecasting models and benchmarking tools for time series analysis. [M4 Forecasting Competition docs](https://github.com/M4Competition/M4-methods)




## Rust Libraries for Time Series Analysis

1. **[polars](https://github.com/pola-rs/polars)** Polars is a fast DataFrame library implemented in Rust. It provides excellent support for time series data manipulation and analysis, offering powerful APIs for filtering, aggregation, and transformation. Polars can be used in Rust and is also available for Python through bindings. [Polars docs](https://pola-rs.github.io/polars/)

2. **[chrono](https://github.com/chronotope/chrono)** Chrono is a comprehensive date and time library for Rust. While not exclusively for time series analysis, it offers robust tools for handling and manipulating dates and times, making it essential for any time series project in Rust. [Chrono docs](https://docs.rs/chrono/)

3. **[plotters](https://github.com/plotters-rs/plotters)** Plotters is a Rust library for data visualization that supports various types of charts, including time series plots. It allows for creating interactive and high-quality visualizations, making it suitable for plotting time series data. [Plotters docs](https://docs.rs/plotters/)

4. **[kdtree](https://github.com/mrhooray/kdtree-rs)** Kdtree is a Rust implementation of a K-dimensional tree for nearest neighbor searching, which can be useful in time series analysis for finding similar patterns or clustering data points based on temporal features. [Kdtree docs](https://docs.rs/kdtree)

5. **[statrs](https://github.com/statrs-dev/statrs)** Statrs is a Rust library for statistical computation. It provides a wide range of statistical functions and distributions, including tools for time series analysis such as moving averages and autoregressive models. [Statrs docs](https://docs.rs/statrs/)


7. **[ndarray](https://github.com/rust-ndarray/ndarray)** Ndarray is a Rust library for working with n-dimensional arrays, similar to NumPy in Python. It supports various operations on multi-dimensional arrays, making it ideal for time series data manipulation and analysis. [Ndarray docs](https://docs.rs/ndarray/)

8. **[hdf5](https://github.com/aldanor/hdf5-rs)** Hdf5 is a Rust interface for the HDF5 data format, which is widely used for storing large datasets, including time series data. It provides efficient I/O operations and supports hierarchical data organization. [Hdf5 docs](https://docs.rs/hdf5/)

9. **[csv](https://github.com/BurntSushi/rust-csv)** Csv is a Rust library for reading and writing CSV files, a common format for time series data. It offers high performance and ease of use, making it a staple for handling time series datasets. [Csv docs](https://docs.rs/csv/)

10. **[rustfft](https://github.com/ejmahler/RustFFT)** Rustfft is a high-performance FFT library for Rust, useful for spectral analysis and frequency-domain transformations of time series data. It supports various FFT algorithms and provides a user-friendly API for time series analysis. [Rustfft docs](https://docs.rs/rustfft/)

11. **[pyo3](https://github.com/PyO3/pyo3)** Pyo3 is a Rust library that enables interoperability with Python, allowing you to use Python libraries like NumPy and Pandas for time series analysis in Rust projects. This is particularly useful for leveraging Python's rich ecosystem of time series tools. [Pyo3 docs](https://pyo3.rs/)

12. **[tch-rs](https://github.com/LaurentMazare/tch-rs)** Tch-rs is a library for using PyTorch in Rust. It enables deep learning and machine learning applications, including time series forecasting with neural networks. [Tch-rs docs](https://docs.rs/tch/)

13. **[linfa](https://github.com/rust-ml/linfa)** Linfa is a comprehensive machine learning framework for Rust that supports various machine learning algorithms, including those suitable for time series analysis such as clustering and regression. [Linfa docs](https://docs.rs/linfa/)

## Contributing

Contributions are welcome! If you have any additional libraries to add, or if you find a bug or have an idea for improvement, please feel free to open an issue or submit a pull request. Follow the [contribution guidelines](CONTRIBUTING.md) for more details.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

