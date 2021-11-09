# pyiron-notebook
my personal jupyter notebook for pyiron-continuum project


In order to use the notebook, one must install: 1) pyrion, 2) pyiron-continuum

The details can be found here:

[pyiron](https://github.com/pyiron/pyiron)

[pyrion-continuum](https://github.com/pyiron/pyiron_continuum)

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
and then put the path of your pyiron-continuum into your `PYTHONPATH`, for instance:
```
export pyiron_continuum=my-path-to-pyiron-continuum
export PYTHONPATH=$PYTHONPATH:$pyiron_continuum
```

# Issues

## 1
```
ModuleNotFoundError: No module named 'pyscal'
```
solution:
```
pip install pybind11
pip install git+https://github.com/pyscal/pyscal
```
## 2
```
ImportError: cannot import name 'Structure' from 'pymatgen' (unknown location)
```
solution:
```
pip install pymatgen==2021.2.16
```

