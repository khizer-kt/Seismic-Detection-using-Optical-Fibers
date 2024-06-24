# Seismic-Detection-using-Optical-Fibers
Normally Earthquake detection is done using specialized equipment, however as there is a huge network of optical fiber cabels all over the world one of their potential benefits that has been observed is their change in behavior in case of an external pressure.  

This data can be recorded on different intervals of time and thus behaves as a time series.  

### Model Selection
Normally for Sequential data Recurrent Neural Networks like LSTMs are used however in our case we used LSTMs with added attention so that they retain their 'memory' for better accuracies.
