<!--
https://pypi.org/project/readme-generator/
-->

[![](https://img.shields.io/pypi/pyversions/readme-badges.svg?longCache=True)](https://pypi.org/project/readme-badges/)
[![](https://img.shields.io/pypi/v/readme-badges.svg?maxAge=3600)](https://pypi.org/project/readme-badges/)
[![Travis](https://api.travis-ci.org/looking-for-a-job/readme-badges.py.svg?branch=master)](https://travis-ci.org/looking-for-a-job/readme-badges.py/)

#### Installation
```bash
$ [sudo] pip install readme-badges
```

#### Functions
function|`__doc__`
-|-
`readme_badges.language(text)` |language badge
`readme_badges.travis(fullname=None)` |travis status badge
`readme_badges.npm.v()` |npm package version badge
`readme_badges.pypi.pyversions()` |python versions badge
`readme_badges.pypi.v()` |pypi project version badge

#### Examples
```python
>>> import pyversions
pyversions = readme_badges.pypi.pyversions()
pypi = readme_badges.pypi.v()
npm = readme_badges.npm.v()
travis = readme_badges.travis()

badges = [pyversions, pypi, npm, travis]
"\n%s" % "\n".join(filter(None, badges))
```

#### Related projects
+   [`classifiers-generator` - python classifiers generator](https://pypi.org/project/classifiers-generator/)
+   [`commands-generator` - shell commands generator](https://pypi.org/project/commands-generator/)
+   [`launchd-generator` - launchd.plist generator](https://pypi.org/project/launchd-generator/)
+   [`readme-badges` - `README.md` badges](https://pypi.org/project/readme-badges/)
+   [`readme-docstring` - generate README.md from python docstrings](https://pypi.org/project/readme-docstring/)
+   [`readme-generator` - `README.md` generator](https://pypi.org/project/readme-generator/)
+   [`setupcfg-generator` - `setup.cfg` generator](https://pypi.org/project/setupcfg-generator/)
+   [`travis-generator` - `.travis.yml` generator](https://pypi.org/project/travis-generator/)

<p align="center">
    <a href="https://pypi.org/project/readme-generator/">readme-generator</a>
</p>