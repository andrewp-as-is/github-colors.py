<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/github-colors.svg?maxAge=3600)](https://pypi.org/project/github-colors/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/github-colors.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/github-colors.py/actions)

### Installation
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
    <a href="https://readme42.com/">readme42.com</a>
</p>
