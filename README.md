# tinypackage
a tiny package to say hello

# installation
pip3 install

# upload to PyPi
# following https://packaging.python.org/tutorials/distributing-packages/
pip3 install -e .
p3 setup.py sdist
p3 install wheel
p3 setup.py bdist_wheel --universal
twine upload dist/*

