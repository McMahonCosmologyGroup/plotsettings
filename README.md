# plotsettings :art: :chart_with_upwards_trend:

Plot settings for uniform figures in group publications.

## Installation

1. `git clone git@github.com:McMahonCosmologyGroup/plotsettings.git`
2. `cd plotsettings/`
3. `python3 setup.py install --user`

## Usage
In jupyter notebook or python script:

```python3
import matplotlib.pyplot as plt
plt.style.use('path/to/repo/plotsettings/matplotlibrc_lab')
```

In your Jupyter notebook, consider adding:
```python3
%matplotlib inline
%config InlineBackend.figure_format = 'retina'
```

## Dependencies
- matplotlib
- setuptools
- Python>=3.7
