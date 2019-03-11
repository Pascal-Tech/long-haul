---
layout: post
title: 'Python: Virtualenv'
date: 2016-11-13 17:18:59
tags:
---


### create a directory to hold new isolated Python environment

```
$ mkdir project_env
$ virtualenv --python=python3 project_env
Running virtualenv with interpreter...
... ...
Installing setuptools, pip, wheel...done.
```

###  activate/deactivate the virtualenv

```
$ cd project_new
$ source bin/activate
(project_env)$

(project_env)$ deactivate
```

