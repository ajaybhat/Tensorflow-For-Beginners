# TensorFlow 101 with Python 3

## <a href=https://www.tensorflow.org/>TensorFlow</a>
"TensorFlow™ is an open source software library for numerical computation using data flow graphs. Nodes in the graph represent mathematical operations, while the graph edges represent the multidimensional data arrays (tensors) communicated between them. The flexible architecture allows you to deploy computation to one or more CPUs or GPUs in a desktop, server, or mobile device with a single API. TensorFlow was originally developed by researchers and engineers working on the Google Brain Team within Google's Machine Intelligence research organization for the purposes of conducting machine learning and deep neural networks research, but the system is general enough to be applicable in a wide variety of other domains as well." 


<a href=https://github.com/ajaybhat/Tensorflow-101/blob/master/1.%20HelloWorld.ipynb>Hello World!</a>

<code>
import tensorflow as tf

with tf.Session() as sess:

print(sess.run(tf.constant('Hello World!')))
</code>


### Installing Conda
Anaconda is available for Windows, Mac OS X, and Linux. You can find the installers and installation instructions at <a href="https://www.continuum.io/downloads" target="_blank" data-unsp-sanitized="clean">https://www.continuum.io/downloads</a>
If you already have Python installed on your computer, this won't break anything. Instead, the default Python used by your scripts and programs will be the one that comes with Anaconda. Choose the Python 3.5 version. After installation, you’re automatically in the default conda environment with all packages installed which you can see below. You can check out your own install by entering <code> conda list </code>

From your terminal, type: 
<code> conda upgrade conda </code>
<code> conda upgrade --all </code>

### Jupyter Notebooks
The Jupyter notebook is a web application that allows you to combine explanatory text, math equations, code, and visualizations all in one easily sharable document. 

By far the easiest way to install Jupyter is with Anaconda. Jupyter notebooks automatically come with the distribution. You'll be able to use notebooks from the default environment.

To install Jupyter notebooks in a conda environment, use <code> conda install jupyter notebook </code>.

Jupyter notebooks are also available through pip with <code> pip install jupyter notebook </code>.
To open Jupyter notebook, Run the following from the root directory of your repository to open up a notebook:
<code>jupyter notebook</code>

### Installing dependencies

<code> conda install --yes --file requirements.txt</code>

Thanks to Udacity and tensorflow.org for text and code samples.
