# tinypackage
a tiny package to say hello

# installation
pip3 install

# upload to PyPi
# following https://packaging.python.org/tutorials/distributing-packages/
pip3 install -e .</br>
p3 setup.py sdist</br>
p3 install wheel</br>
p3 setup.py bdist_wheel --universal</br>
twine upload dist/*</br>

