# Senior Design Spring 2025 Team 1725
## ECE Senior Design Spring 2025. Classifying Invasive Species using Drone Images and Deep Learning.
These are colab notebooks Ziek Moreno used to complete Task 5 in our project. There is 3 different notebooks:
- The initial notebook using the yolov11 model both Landon and Joey were using at the time toi guage an idea of how to set the models up
- A first test run using our alternative model yolov8 to make sure everything worked ok and was ready for larger testing with more images
- A version 2 of this notebook where I tested with more images using all 4 classes to try and maximize the results.

## About the Notebooks:
- Each note book starts by mounting a dataset from our team's Microsoft Sharepoint into the colab instance.
- From there the dataset is split up as needed for training, validation, and testing sets
- after which they are used for the training in the Yolov8-cls model
