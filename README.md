# TMRDataSet2020

This repository contains the TMRDataSet2020 dataset presented in the paper "Automatic Transportation Mode Recognition on smartphone data based on Deep Neural Networks" currently undergoing peer review. 

All the data gathered by the Repository owner is made public. The repository is currently a work in progress, as it will be populated more and refined by the authors before publication.

Interested researchers are encouraged to share their data to enrich this collection. 
The only requirement we have is that the data format is consistent with the one presented above; other transportation modes can be added in a dedicated folder. 

If this data is useful for your research please reference this repository.

The data format = ["Signal Strength","Speed","Acc_x_axis","Acc_y_axis","Acc_z_axis","Gyro_x_axis","Gyro_y_axis","Gyro_z_axis","Mag_x_axis","Mag_y_axis","Mag_z_axis","transportation mode"]

If a signal is not available for measurement for any reason (typically gps related signals, as "Speed", or "Signal Strength") please set it as "None".
