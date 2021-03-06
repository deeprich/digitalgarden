---
title: "python"
layout: single-series
weight: 3
subtitle: ""
excerpt: "Python Environments"
draft: false
---
{{< figure src="/img/xkcdpy.png">}}

Image: [XKCD]("https://xkcd.com/1987/") shows what **not** to do, the way to avoid this is to use environments.  Following general plan of minimising bloat, I prefer to avoid conda (about 3GB of stuff I won't use). The general virtual environment choice is a bit of a [rabbit hole]("https://stackoverflow.com/questions/41573587/what-is-the-difference-between-venv-pyvenv-pyenv-virtualenv-virtualenvwrappe") though.

## Prerequisites
Install python3
```
brew install python
python3 -V
pip install --upgrade pip
```

Within VS Code environments add ```python``` to set up the development environment.

Create virtual environment and add packages as req:
```
python3 -m venv <<folder name>>
source .venv/bin/activate
```
To exit the environment
```
deactivate
```




