# MSc Research Project Code Files

This repository contains all the relevant files of my MSc Research Project - Financial Volatility Forecasting in Exchange Rate Market. The project thoroughly analyses the volatility forecasting in the exchange rate market, investigates the statistical properties of realized variance and develops methods to improve the predictive performance of both point forecast and probabilistic forecast in both univariate and multivariate settings.

### Data source
The raw data for this project is downloaded from TRUEFX (https://www.truefx.com/). One first needs to register an account. Then under 'Market Data' -> 'Historical Downloads', one could download the high-frequency price data for different currency pairs of the past year.

### Directory structure
The outputs and code of the project are structured as follows:
-   **01714151_project_report.pdf/**: The final report of the research project.

-   **01714151_project_poster.pdf/**: The presentation poster on the early findings of the project.

-   **univariate_model & analysis/**: The directory contains the files of all data analyses, model fitting and evaluation in the univariate setting. `univariate_workspace.RData` is a saved workspace that contains all the final output data for univariate analysis, and it can be loaded directly to save time. **univariate_analysis/** and **univariate_model_fitting/** are two sub-directories which store the `.Rmd` files for evaluation and model-fitting separately. **univariate_analysis/** contains the `.Rmd` files for basic exploratory analysis, adjusted ratio jumps, univariate models evaluation and comparison, forecast aggregation, residuals GH distribution fitting and probabilistic forecast. **univariate_model_fitting/** contains all the `.Rmd` files for constructing and fitting all proposed univariate point-forecast models.

-   **multivariate_model & analysis/**: This directory contains the files of all data analyses, model fitting and evaluation in the multivariate setting. `multivariate_workspace.RData` is the saved workspace which contains all the final results in the multivariate part and can be loaded directly. The directory also includes all the `.Rmd` files for exploratory analyses, portfolio variance forecasts, residuals bivariate GH distribution fitting and copula models fitting.

-   **images/**: This directory contains all the images produced by the code and used in the final report.

### Results reproduction
The results and images presented in the report can be reproduced with the `.Rmd` files in the **univariate_model & analysis/** and **multivariate_model & analysis/** directories. Just run the `.Rmd` files in the numbering order of their file names, and one is able to reproduce all the results.

### Note
This project is completed individually by the student of CID 01714151. Should any error be spotted or further enquiries be raised regarding the project, feel free to email the author through jz4919@ic.ac.uk. It is currently a private project shared exclusively within the Statistics Department of Imperial College London. The viewer shall not distribute the repository link without the permission from the author.

