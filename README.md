# Steering-wheel-angle-prediction

We have published paper in International Research Journal of Engineering and Technology (IRJET) Volume 7, Issue 3, March 2020 S.NO: 924
[Our published paper](IRJET-V7I3924.pdf)

**Self-driving cars** are one of the most increasing interests in recent years.
Convolutional Neural Networks(CNNs) have been shown to achieve significant performance in various perception and control tasks compared to other techniques in the latest years. So we are using CNN in this project.

**Steps**
1. Collect data while manually driving the car in a simulator
2. Train a deep neural network to mimic the driving based on training data
3. Let the model run in the simulator to drive for itself

You should have a
```
driving_log.csv
```
file with telemetry data and an
```
IMG/
```
folder with thousands of images captured from your driving session.


Our next job is to read from the CSV file, the names of the images and their related steering data and load the respective image from the IMG folder in Python.

We are using google colab(since it provides free GPU)

Train the model, and test it using simulator.


[Project PPT](Major_Project.pptx)

