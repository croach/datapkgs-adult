# datapkgs-adult

The [Census Income Data Set][1] (aka, the Adult data set) from the [UCI Machine Learning Repository][2].

## Installation and Usage

To use use this data set you must first install the [datapkgs][3] library. 

```
pip install datapkgs
```

After installing the datapkgs library, you import the library from within your project with the following line of code.

```python
from datapkgs import adult
```

The previous statement above will import a [pandas DataFrame][4] that contains the complete Adult data set as well as attributes that describe the data within.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

[1]: http://archive.ics.uci.edu/ml/datasets/Census+Income
[2]: http://archive.ics.uci.edu/ml/index.php
[3]: https://github.com/croach/datapkgs
[4]: https://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.html
