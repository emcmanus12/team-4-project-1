# Fed Rate Impact Predictor


## Overview

Fed Rate Impact Predictor is a Python application designed to analyze the impact of Federal Reserve interest rate changes on unemployment rates. The project aims to answer the question: "What would a decrease in interest rates, coupled with inflation nearing its target range, mean for unemployment?"

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Analysis](#analysis)
4. [Contributers](#contributers)
5. [Conculusion](#conclusion)

## Installation

Provide instructions on how to install your Python application. Include any dependencies that need to be installed and how to install them (e.g., using pip).

```bash
!pip install plotly-express
```

## Usage

To use this application, follow these steps:

1. **Clone the Repository**
    - Navigate to the "Code" drop-down menu on the repository page.
    - Copy the SSH URL.

2. **Set Up Your Project Directory**
    - Open your terminal.
    - Create a new directory for the project:
      ```bash
      mkdir fedrateimpactpredictor
      ```
    - Change to the new directory:
      ```bash
      cd fedrateimpactpredictor
      ```

3. **Clone the Repository**
    - Clone the repository using the copied SSH URL:
      ```bash
      git clone <git@github.com:emcmanus12/team-4-project-1.git>
      ```

4. **Run the Jupyter Notebook**
    - Launch Jupyter Notebook:
      ```bash
      jupyter notebook
      ```
    - Open the relevant notebook file and run through the cells to get your outputs.

## Analysis

### Question

The Federal Reserve is poised to decrease interest rates, as inflation continues to get closer to its target range. What would this mean for unemployment?

### Approach

- **Correlations between Unemployment & Inflation**: Analyze the correlation between unemployment and inflation.
- **Correlation between Unemployment & Interest Rates**: Examine the correlation between unemployment and interest rates.
- **Forecasting Unemployment with Prophet**: Use Prophet to forecast unemployment based on assumptions of lower interest rates and inflation.

# Conclusion 

1. **Unemployment and Inflation**: There's a connection between unemployment and inflation rates. When inflation drops, unemployment tends to decrease as well, especially when looking at data from two years ago.
![Inflation](./images/inflation.png)

2. **Unemployment and Fed Funds Rate**: Similarly, when the Federal Reserve lowers interest rates (Fed Funds Rate), unemployment often decreases. This trend is particularly noticeable when considering past unemployment rates.
![Fed Funds Rate](./images/fed_funds_rate.png)

3. **Prophet Forecast Model**: Using a forecasting model called Prophet, we can predict that unemployment rates will likely decrease in the future for all states.
![forecast](./images/forecast_CA.png)

4. **Pandemic Analysis**: Nevada (NV) was hit hardest by the pandemic and is still struggling to fully recover. This is reflected in the state's high unemployment rates.
![Pandemic](./images/pandemic.png)

## Contributers

Ian Cody,
Jaidev Kler,
Ethan McManus,
Kyle Prudente,
Grigoriy Isayev,
Emmanuel Charles.
