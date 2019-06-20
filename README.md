# Problem Statement:

Transform iris data into 3 dimensions and plot a 3d chart with transformed dimensions and color each data point with specific class.

### Code to load data

    import numpy as np
    import matplotlib.pyplot as plt
    from mpl_toolkits.mplot3d import Axes3D
    from sklearn import decomposition
    from sklearn import datasets
