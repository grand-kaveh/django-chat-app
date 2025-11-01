- UI UX




pip install setuptools wheel twine
python setup.py sdist bdist_wheel
pip install dist/django_chatapp-2.0-py3-none-any.whl --force-reinstall
pip list
twine check dist/*
twine upload dist/*
