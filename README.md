# Dreamify Image Using Neural Networks

# About

This is an experiment that visualizes the patterns learned by a neural network. Similar to when a child watches clouds and tries to interpret random shapes, Dreamify over-interprets and enhances the patterns it sees in an image.

it does so by forwarding an image through the network, then calculating the gradient of the image with respect to the activations of a particular layer. The image is then modified to increase these activations, enhancing the patterns seen by the network, and resulting in a dream-like image. This process was dubbed "Inceptionism"

# Results

![Normal picture of a pug](assets/photos/pug.jpg)
![1st level of dreamified pug](assets/photos/dreampug1.png)
![2nd level of dreamified pug](assets/photos/dreampug2.png)
![3rd level of dreamified pug](assets/photos/dreampug3.png)

# Pre-requisite downloads

install if you don't already have the required libraries

```
pip install tensorflow
pip install matplotlib
pip install ipython
```

# How to run

1. Download required packages <br>
2. Open dreamify.ipynb
3. set path to the photos (can be located locally or via https link)
4. Run cell from top to bottom and watch your photo become dreamified!

# Next Steps

Will work on a GUI for this project so its easier to use
