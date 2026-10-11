# Bootstrap and Monte Carlo Simulation for Earthquake Data

## About
This project compares Bootstrap and Monte Carlo resampling methods to estimate the mean, skewness, and kurtosis of earthquake magnitude data.

## Data
- **Source:** [Meteorology, Climatology, and Geophysical Agency (BMKG)](https://www.bmkg.go.id/)
- **Period:** March 3–7, 2025
- **Coverage:** Earthquakes in Indonesia
- **Magnitude:** Greater than 3
- **Variable:** Earthquake magnitude
- **Data Type:** Secondary data

## Methods
1. **Data Preparation** — Load and prepare earthquake magnitude data.
2. **Normality Testing** — Apply Shapiro–Wilk and Kolmogorov–Smirnov tests.
3. **Bootstrap Resampling** — Generate 1,000 samples with replacement for sample sizes of 50, 100, 500, and 1,000.
4. **Monte Carlo Simulation** — Generate samples from a Kernel Density Estimation (KDE) fitted to the original data.
5. **Parameter Estimation** — Calculate the mean, skewness, and kurtosis for each simulated sample.
6. **Performance Evaluation** — Compare estimator values, variance, absolute bias, and Mean Squared Error (MSE).
7. **Visualization** — Compare sampling distributions using histograms and density curves.

## Author
**Sandra Berliana Putri** - Statistics and Data Science graduate from IPB University, interested in statistical modeling and data analysis.
