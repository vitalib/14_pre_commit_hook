# Quadratic Equations Solver 
Script provides a function get_roots that solves quadtratic equation. 

# Quick Start
Script should be run by Python3.5.
Example of utilization on Linux
```bash
$python3
3.5.2 (default, Sep 14 2017, 22:51:06) 
[GCC 5.4.0 20160609] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> from quadratic_equation import get_roots
>>> x1, x2 = get_roots(1, -2, 1)
>>> x1, x2
(1.0, None)
```

Pre-commit hook that runs tests may be installed as follows:
```bash
chmod +x pre-commmit
cp pre-commit .git/hooks/
```

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
