# Seismic-Detection-using-Optical-Fibers
Normally Earthquake detection is done using specialized equipment, however as there is a huge network of optical fiber cabels all over the world one of their potential benefits that has been observed is their change in behavior in case of an external pressure.  

This data can be recorded on different intervals of time and thus behaves as a time series.  

### Model Selection
Normally for Sequential data Recurrent Neural Networks like LSTMs are used however in our case we used LSTMs with added attention so that they retain their 'memory' for better accuracies.

### Problems and the Solution
The dataset has 4 distinct classes 0,1,2,3 these are the levels of the seismic activity happening at any time step. The most important class is class '1' as it acts as an early warning for an earthquake, however the dataset is shaped as such that using any architecture normally yields zero precision on this class. We used class weights during training and assigned the highest weight to class '1' to cater to this problem.

### Working on
Still working on improving the accuracy of the models being used.
