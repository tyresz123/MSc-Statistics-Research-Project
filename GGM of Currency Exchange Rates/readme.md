# Project Overview

This project explores the complex interdependencies within the global currency market using advanced statistical techniques. The primary aim is to improve macroeconomic policy formulation and financial strategy development.

## Objectives

- **Gaussian Graphical Models (GGMs)**: Analyze direct conditional dependencies among currency exchange rates. This approach surpasses traditional methods that rely on simple correlation matrices and Minimum Spanning Trees, which often misrepresent causality and overlook temporal dynamics.

- **Data Utilization**: Use a decade of international exchange rate data (from June 2014 to June 2024) across 25 currencies. Employ GGMs to uncover the underlying network structure. We introduce innovative penalties based on edge count to refine our model and optimize hyperparameters. Additionally, we explore dynamic network forecasting through the Temporal Exponential-Family Random Graph Model (TERGM), which effectively captures evolving relationships using historical network data.

- **Hybrid Predictive Framework**: Integrate a Deep Autoregression Model (DeepAR) with GGMs, creating a hybrid approach that combines time series forecasting with network analysis. This dual methodology allows for more robust predictions of currency trends and interactions, highlighting the practical benefits of combining diverse analytical techniques to address the dynamic nature of financial markets.

- **Research Significance**: By employing GGM, TERGM, and DeepAR models, we enhance the prediction of international exchange rates. Our method, which adjusts the covariance matrix and optimizes model parameters, offers a nuanced and adaptive framework. Unlike previous studies that used static covariance matrices or simpler models, our approach reflects real-time market changes. Future research could further refine covariance estimation methods and expand datasets to include diverse market conditions, enhancing prediction accuracy.

## Data

The data used for this project is sourced from the Bank of England's website and can be downloaded from [Bank of England Data](https://www.bankofengland.co.uk/boeapps/database). 

- **data.csv**: Daily spot exchange rates against the Great Britain Pound.

## Source Code

The following scripts and results are included:

- **`final_glasso.Rmd`**: Script for Graphical Lasso Tuning and Network Construction.
- **`tergm.Rmd`**: Script for the TERGM model and currency network prediction.
- **`deepar_little_dat.ipynb`**: Script for the DeepAR model and prediction.
- **`final_glasso.html`**: Results for Graphical Lasso Tuning and Network Construction.
- **`tergm.html`**: Results for the TERGM model and currency network prediction.

## License

This project is open source and available under the MIT License.

## Contact

For any further queries or suggestions, feel free to contact us at [your contact information].

