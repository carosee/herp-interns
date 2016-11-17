# herp-interns/week3
Week 3: Numpy

## Thursday, Nov 10
- Finish up DNA/Transcription/Translation coding exercise from last week: See <https://github.com/carosee/herp-interns/tree/master/week2>
- Go over project description document I sent via email. If you need a break from coding or you finish something early, read over this!
- How would I store & access a table of values in Python?
- Numpy intro

### Numpy Intro
- download and import numpy
- create a 1 dimensional numpy array
- numpy.shape
- index into a numpy array
- create a 2 dimensional numpy array
- index into a 2D numpy array
- loop through a 2D numpy array
- create a 2 dimensional numpy array of 0s
- get a row from a numpy array
- get a column from a numpy array
- array math and vectorization

#### Installing Numpy

There are 3 important packages that you should have for your research projects: numpy, scipy, and matplotlib. Check that you have them installed by opening a Python terminal and attempting to import them:

```python
import numpy
import scipy
import matplotlib
```

If you get an `ImportError: No module named sdf`, this means these packages have not been installed. If you don't, then great! Move on to the next section.

To install all of these packages at once, we are going to install a python distribution known as Anaconda, which can be found here: https://www.continuum.io/downloads. Follow the instructions to download and install the Anaconda distribution for Python 2.7.

