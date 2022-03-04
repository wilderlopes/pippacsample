Sample pip package

Based on the tutorial from https://towardsdatascience.com/how-to-publish-a-python-package-to-pypi-7be9dd5d6dcd

Step 1.

```bash
python -m pip install –-user –-upgrade setuptools wheel 
```

Step 2.

```bash
python setup.py sdist bdist_wheel
```



