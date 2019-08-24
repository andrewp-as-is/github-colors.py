<!--
https://pypi.org/project/readme-generator/
https://pypi.org/project/python-readme-generator/
-->

[![](https://img.shields.io/pypi/pyversions/github-colors.svg?longCache=True)](https://pypi.org/project/github-colors/)
[![](https://img.shields.io/pypi/v/github-colors.svg?maxAge=3600)](https://pypi.org/project/github-colors/)
[![Travis](https://api.travis-ci.org/andrewp-as-is/github-colors.py.svg?branch=master)](https://travis-ci.org/andrewp-as-is/github-colors.py/)

#### Installation
```bash
$ [sudo] pip install github-colors
```

#### Examples
`COLORS` dict
```python
>>> import github_colors
>>> github_colors.COLORS
{
    '1C Enterprise': '#814CCC',
    ...
}
```

`get(name,default)` (default color is `#ccc`)
```python
>>> github_colors.get('1c enterprise')
'#814CCC'

>>> github_colors.get('awk','#ccc')
'#ccc'
>>> github_colors.get('not-existing','#ccc')
'#ccc'
```

<p align="center">
    <a href="https://pypi.org/project/python-readme-generator/">python-readme-generator</a>
</p>