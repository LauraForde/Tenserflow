# Tensorflow

> Emerging Technologies 4th Year [module](https://emerging-technologies.github.io/)  
> Taught by Dr Ian McLoughlin  
> Solve four [problems](https://emerging-technologies.github.io/problems/tensorflow.html) based on the [Iris](https://archive.ics.uci.edu/ml/datasets/iris) data set using the Python package Tensorflow.

For completing these tasks tensorflow and keras must be installed. You can run the command pip install tensorflow/keras. When I was doing this I ran into problems, I was getting errors stating that the module was not found when I was trying to import to my Jupyter notebook. I fixed this by opening a command prompt as admin and used the same line of code. I was using cmder to try and install the modules at first but was told there was permission errors. I fixed it by doing the admin command prompt and then the import worked perfectly.

**Exercise 1 - Use Tensorflow to create model**  
We are to use Tensorflow to predict the species of Iris from the flower's sepal width, sepal length, petal width and petal length.

**Exercise 2 - Split data into training & testing**  
We must split the Iris data into two sets; training and testing. To do this we are allowed to write our own code that will randomly seperate the data on the fly and investigate the best possbile way for this to do done.

**Exercise 3 - Train the model**  
We are expected to use the testing set to train the model.

**Exercise 4 - Test the model**  
We are to use the testing set to test the model, clearly calculating and displaying the error rate of this.