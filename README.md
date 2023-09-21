# Farmland-Parcel-Dataset
About A Farmland Parcel Dataset based High-Resolution Remote Sensing Images
To address the lack of public dataset of cropland parcels that can be used for deep learning model training, we adopts ArcGIS software to manually label the samples in the images based on two GF-2 remote sensing images which are located in different regions, such as Funan County, Anhui Province and Ruian County, Zhejiang Province. We cropped them into 1,761 tiles with 512×512 pixels. The ready-to-use samples are divided into three parts: a training set (1,059 tiles), a validation set (351 tiles) and a test set (351 tiles).

The main types of farmland included in our dataset are: dryland, paddy field, fallow land and shed-grown land.

We took into account the diversity of cropland types and spatial distribution differences, and selected the sample construction area on the premise of including all cropland types as far as possible and ensuring the completeness of the sample. In the process of vector data production, we strictly follow the cross-checking method to ensure the quality of the dataset.

Finally we produced three formats based on the characteristics of three different types of tasks: semantic segmentation, edge detection and instance segmentation.
