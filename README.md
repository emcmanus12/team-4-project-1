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

All three analysis indicate a drop in unemployment, if the Federal reserve were to cut the Fed Funds rate based on inflation moving towards its target range.
1. Unemployment and PCE Inflation rate have a low-moderate correlation depending on the state. There is a stronger correlation between lagged (24 months) unemployment and PCE inflation. This implies unemployment will fall if PCE inflation rate continues to drop.
2. Unemployment and Fed funds rate have a low-moderate correlation depending on the state. There is a stronger correlation between the lagged unemployment and Fed Funds rate. This would imply unemployment will continue to fall if the Fed starts to reduce the Fed Funds rate.
3. The Prophet forecast model shows a downward trend in unemployment rates for all states.
Additional analysis were carried out after reviewing the results of the three analysis, as there were two anomalies (CA and NV) in the results. The anomalies showed unemployment had no correlation with PCE inflation rate or Feds Funds rate.
4. Pandemic Analysis - This showed that NV was the worst affected state and had still not recovered completely from the pandemic.

## Contributers

Ian Cody,
Jaidev Kler,
Ethan McManus,
Kyle Prudente,
Grigoriy Isayev,
Emmanuel Charles.
