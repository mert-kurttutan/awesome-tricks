# awesome-tricks
This is a list of ways/tricks to deal with some software issue, with strong documentation


## Theme-Enabled Readme Docs on PyPI
> When you use readme.md on github that behaves different based on theme as a part of python package, e.g. [**here**](https://github.com/mert-kurttutan/torchview/blob/main/README.md), this readme is not rendered correctly on pypi. To do remedy this, you can use a trick on github CI where you essentially transform readme.md file so that it removes theme-related part, originated from this [**commit**](https://github.com/charliermarsh/ruff/pull/2287), see [here](https://github.com/mert-kurttutan/torchview/blob/main/scripts/transform_readme.py) for the file of transformation. A relevant issue can be found [here](https://github.com/pypi/warehouse/issues/11251)
