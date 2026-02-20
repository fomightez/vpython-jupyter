# VPython working in Jupyter served via MyBinder service.

Please refer to https://github.com/vpython/vpython-jupyter is you are interested in current VPython development.

If you just want a MyBinder-served session that has VPython working, try this launch badge:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/vpython-jupyter/HEAD?urlpath=%2Ftree%2Findex.ipynb)

### Impetus for the fork
This fork is presently just to restore VPython working from MyBinder launches because when I tried in February 2026 using the launch link here, I was getting something that said `AttributeError: module 'notebook' has no attribute 'nbextensions'` (like [here](https://github.com/vpython/vpython-jupyter/issues/254)) when I tried to run the demostration notebooks. **Maybe I was using the wrong branch?** I know Vpython and Jupyter presently only works with Python 3.12, and so I thought while trying to get it working from launch badge I'd make one that should work a bit longer via MyBinder launches by specifying 3.12. That is the current version you get with MyBinder launched by default but who knows how much longer that will be the case. And so I'll set it for now. See https://github.com/fomightez/vpython-jupyter/blob/master/binder/environment.yml .  
In addition to specifying the Python version, I added some packages I commonly use. And so keep in mind it can be even easier than this if you don't need those othter packages yourself.


## If you prefer your choice of Jupyter interface....

JupyterLab interface: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/vpython-jupyter/main?urlpath=%2Flab%2Ftree%2Findex.ipynb)  
Jupyter Notebook 7+:  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/vpython-jupyter//main?urlpath=%2Ftree%2Findex.ipynb)