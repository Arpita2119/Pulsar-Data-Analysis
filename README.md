# Pulsar-Data-Analysis
# Vela Pulsar Signal Analysis

This project was developed during a summer research internship and focuses on analyzing Vela pulsar radio signals using Python in Google Colab.
- Performed Fast Fourier Transform (FFT) to extract frequency components from raw signal data
- Generated power and dynamic spectra to visualize signal strength over time and frequency
- Applied dedispersion using dispersion measure (DM) to correct time delays in signal
- Folded and fit the pulse profile using Gaussian models to study pulse shape

The dataset 'New Data' is a plain text file containing voltage time series data. It is read using `pandas.read_table()` with appropriate delimiters.

#Tools Used
- Python (NumPy, Pandas, Matplotlib, SciPy)
- Google Colab
- Signal processing techniques in radio astronomy
