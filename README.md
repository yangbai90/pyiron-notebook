# pyiron-notebook
my personal jupyter notebook for pyiron-continuum project


To use the notebook, one must install: 1) pyrion, 2) pyiron-continuum

# For pyiron
Installation can be done via:
```
pip install pyiron
```

# For pyiron-continuum
One can use either:
```
pip install pyrion-continuum
```
or
```
git clone https://github.com/pyiron/pyiron_continuum.git
```
and then put the path of pyiron-continuum into your `PYTHONPATH`, for instance:
```
export pyiron_continuum=my-path-to-pyiron-continuum
export PYTHONPATH=$PYTHONPATH:$pyiron_continuum
```
