# Car License Plate Detection System in Parking Lot
## Goal: how to recoginize  quickly the vehicles license plate to reduce operating expenses and keep clients satisfied.

In the project, we use the dataset from  [Kaggle](https://www.kaggle.com/datasets/andrewmvd/car-plate-detection) to collect the vehicle images where the number plate appears.This dataset contains 433 images with bounding box annotations of the car license plates within the image.

![ Example ](https://github.com/thivnguyen1/Car-License-Plate-Detection/blob/66c5046909670eb796b43cb59b2e7be81263e095/Images/CLPbox.png)

We use pre-train VGG16 and RESNET50 on the license plate dataset. This means reusing the weights in one or more layers from the pre-trained network models in a new model and  keeping the weights fixed. We also add some more news layer and  fine tuning them.

### Working directory structure

1. [Project proposal](https://github.com/thivnguyen1/Car-License-Plate-Detection/blob/e13150568f55700fd3815f491aeb346e25a0feb8/Project%20Proposal%20.pdf)

2. [Final Notebook](https://github.com/thivnguyen1/Car-License-Plate-Detection/blob/f64d86ed39a4b7f7673ec55f9e8b47f56e60bba4/Final_Notebook_Car_lincense_Plate_Detection%20.ipynb)

3. [Slide present](https://github.com/thivnguyen1/Car-License-Plate-Detection/blob/f64d86ed39a4b7f7673ec55f9e8b47f56e60bba4/Slide_presentation.pdf)

4. [Images](https://github.com/thivnguyen1/Car-License-Plate-Detection/blob/f64d86ed39a4b7f7673ec55f9e8b47f56e60bba4/Images/CLPbox.png)

