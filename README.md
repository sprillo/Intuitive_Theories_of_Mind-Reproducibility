# Intuitive_Theories_of_Mind-Reproducibility

Here we reproduce the results in the paper ["Intuitive Theories of Mind: A Rational Approach to False Belief"](http://web.mit.edu/cocosci/Papers/pos785-goodman.pdf) by Goodman et al.

Make sure you have jupyter installed. To be able to run the notebook create a new python environment and add it to your jupyter notebook kernels as follows:

```
$ virtualenv -p python3 env
$ source env/bin/activate
$ pip install -r requirements.txt
$ pip install ipykernel
$ python -m ipykernel install --user --name intuitive_tom_reproducibility --display-name "Python (intuitive_tom_reproducibility)"
```

The pinned requirements are also available.

The notebook takes a few minutes to run end-to-end.

To convert the notebook to slides and view the presentation in your browser:

```
$ jupyter nbconvert Intuitive_Theories_of_Mind-Reproducibility.ipynb --to slides --post serve
```
