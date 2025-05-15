# _mHVSR-Vs30_ - A Set of Data-driven models to predict Vs30 from mHVSR

> Kushal Sharma Wagle, Adrian Rodriguez-Marek, Joseph P. Vantassel [jpvantassel.com](https://www.jpvantassel.com/)

## Table of Contents

-   [About _mHVSR-Vs30_](#About-mHVSR-Vs30)
-   [Getting Started](#Getting-Started)

## About _mHVSR-Vs30_

`mHVSR-Vs30` is a collection of data-driven models to predict the
time averaged shear wave velocity in the upper 30 m (Vs30), from 
microtremor horizontal-to-vertical spectral ratio (mHVSR). The developed
models developed include both low-dimensional (`low_dim_models.ipynb`) and
high-dimensional (`high_dim_models.ipynb`). The details of the model's
development and performance are presented in the reference below.

If you use these tools in your research or consulting, we ask you please cite the
following:

> Sharma Wagle, K., Vantassel, J.P., and Rodriguez-Marek, A. (2025). "A Set of Data-Driven Models to Predict VS30 from the
> Horizontal-to-Vertical Spectral Ratio of Microtremors". Bulletin of the Seismological Society of America. [In-Review]

## Getting Started

### Installing _mHVSR-Vs30_

1.  If you do not have Python 3.10 or later installed, you will need to do
so. A detailed set of instructions can be found
[here](https://jpvantassel.github.io/python3-course/#/intro/installing_python).

2. Download a copy of the repository to your local machine. This can be done by
downloading a .zip file or by cloning the repository. If you download a .zip you
will need to be sure that you continue using the unzipped version to prevent issues.

3.  Install the Python dependencies using `pip` via the command `python -m pip install -r requirements.txt`.
If you are not familiar with `pip`, a useful tutorial can be found
[here](https://jpvantassel.github.io/python3-course/#/intro/pip).

4.  Confirm that the dependencies have installed/updated successfully by examining the
last few lines of the text displayed in the console.

### Using _mHVSR-Vs30_

1.  Launch the provided Jupyter notebooks, `low_dim_models.ipynb` or `high_dim_models.ipynb` (recommended),
  for a no-coding-required introduction to prediction models. If you have not installed `Jupyter Lab`,
  detailed instructions can be found [here](https://jpvantassel.github.io/python3-course/#/intro/installing_jupyter).

2.  Continue to explore the three datasets provided by changing the file names and associated metadata in the
  notebooks. Once you feel comfortable running the example data you can then apply the models on any mHVSR data
  of interest.

3.  Enjoy!
