---
title: notebooks
permalink: /notebooks/
---

<!-- #region -->
Links to the [Jupyter notebooks](http://jupyter.org/) making up this module can be found here: 
[lecture series](http://matt-piggott.github.io/Numerical-methods-undergraduate/lecture_series/).

To run and edit the notebooks yourselves we have several options:

### Edit and run them locally using Anaconda
It is possible to run everything on your desktop/laptop - this is a good option if you have firewall or internet issues. Anaconda should be installed on departmental machines. To install yourself look at [Anaconda](https://www.anaconda.com/download/) and choose Python 3.x. You can then download the notebooks from the github repo for this module and run them locally.  On Windows, to use Anaconda to run Jupyter notebooks search for 'Jupyter' and click on the 'Jupyter Notebook (Anaconda3)' app.


### Using cloud based solutions - Google Colab

`Google Colab` is an option if you don't want to install Anaconda locally: [https://colab.research.google.com/notebooks/intro.ipynb](https://colab.research.google.com/notebooks/intro.ipynb).

You will need to register for a Google Account - if you don't already have an account you can make a throwaway account if you do not want Google to have your data.

If you have trouble connecting to this service try using the College VPN.

You can upload a notebook using

`File -> upload`

You can also mount your Google Drive with the following commands
```python
from google.colab import drive
drive.mount('/content/gdrive/')
```
See [here](https://www.marktechpost.com/2019/06/07/how-to-connect-google-colab-with-google-drive/) for more information.


Google Colab (should) store your notebooks automatically, but it can never hurt to save and store your work locally:

`File -> Save`

and then download a copy of the .ipynb file:

`File -> Download .ipynb`
<!-- #endregion -->

Back to main page: [https://matt-piggott.github.io/Numerical-methods-undergraduate/](https://matt-piggott.github.io/Numerical-methods-undergraduate/)
