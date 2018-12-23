# Spectrum-Analyzer-and-Filter-Design-Tool
Implementation of a software Spectrum Analyzer and Filter Design Tool with a Graphical User Interface
The app can be used using the mainapp file, you must have matlab installed.
Discrete Convolution:
This mode computes the discrete convolution of two signals sampled with the same sampling frequency. It plots 
the two signals in the time domain and four stages of the convolution process in linear or logarithmic scale.
The signals that are going to be convolved, the sampling frequency and the plotting scales are chosen by the user.
Spectrum Analyzer: 
The mode takes a signal as an input, applies a window to it, then plots the signal in the time domain and 
the frequency domain on linear or logarithmic scales. It also calculates important quantities like RMS Average, Peak of the Signal,
Power of the Signal and the Absolute value of the DC bias.
Comparison Mode:
The Mode takes two signals as an input, applies a certain window to each of them, then plots the two signals in the time domain
and the frequency domain on a linear or a logarithmic scale.
Filter Design Mode:
The application takes user specified filter specifications as an input (Filter order, Passband Frequency & Stopband Frequency) 
and approximates the filter using least squares method and calculates the least squares error. It plots the frequency response 
of the filter on a linear or a logarithmic scale. It also provides different plotting options (Magnitude, Phase, Real and Imaginary). 
