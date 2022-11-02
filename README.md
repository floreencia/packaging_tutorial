# Python package example

This is an example from the tutorial [Packaging Python Projects](https://packaging.python.org/en/latest/tutorials/packaging-projects/)

https://test.pypi.org/project/example-package-florenius/


## Personal notes

Follow instructions in [this totorial](https://packaging.python.org/en/latest/tutorials/packaging-projects/)

### The tutorial in a nutshell

* We go over the steps of packaging code and uploaded to [test.pypi](https://test.pypi.org/), an index for testing packages, before uploading them to the [pypi index](https://pypi.org/)
*  You'll nned to create some files (eg. __init__.py, pyproject.toml, LICENSE, README) and directory structure (src, tests) and other files will be created duting the packagiing process (*.egg-info, *.tar.gz, *.whl)
* You'll need accounts in
    * [test.pypi](https://test.pypi.org/) to add packages to the tetspypi index 
    *  [Twine](https://packaging.python.org/en/latest/key_projects/#twine) to upload packages to the index via the cl
* Once your package is ready, and beautifully working in test.pypi, you can add it to the [pypi index](https://pypi.org/)