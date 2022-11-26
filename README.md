# Time Series Analysis of Covid-19 India data
Time Series Analysis and Forecasting of Covid 19 India dataset date (Jan 2020 to Aug 2021)
## DataSet Description
Dataset is downloaded from https://www.kaggle.com/datasets/sudalairajkumar/covid19-in-india
It contains Time, Date, State/UT, Cumulative covid-affected cases, cured, and deaths
## Data Pre processing
The above dataset is converted into time series data and state-wise by Hierachial Indexing using Pandas DataFrame
Cumulative data is converted to daily cases-data
Preprocessed data is stored as preprocessed.csv 
## Exploring Data
Print min, max and various combinations
## DateTime Features
Print, Date, Rolling mean, expansion mean
## Visualisations
Plotting in various samples and resampling data, monthly data, weekly data
Various Plots:
  1. Line Plots.
  2. Histograms and Density Plots.
  3. Box and Whisker Plots.
  4. Heat Maps.
  5. Lag Plots or Scatter Plots.
  6. Autocorrelation Plots.
  
## Resampling and Interpolation
Upsampling and Downsampling and using ffill, interpolation
## Power Transformation
Log, Sqrt and Box-Cox and their acffuller test
log transform results in -INF due to 0 value
## Average Smoothing
Moving and Exponential Average and prediction
