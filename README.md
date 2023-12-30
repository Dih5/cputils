# cputils

[![license MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE.txt)

Utilities for Competitive Programming. 

Features:
- Download samples from [kattis](https://open.kattis.com/), [aceptaelreto](https://aceptaelreto.com/).
- Test in c, cpp, python, java, rust, ruby, bash.
- Submit to kattis.

Tests only for complete textual match, ignoring leading and trailing whistespaces. 

## Installation
Assuming you have a [Python3](https://www.python.org/) distribution with [pip](https://pip.pypa.io/en/stable/installing/), install the package running:

```bash
pip3 install cputils
```

## Usage
### cpconfig
To create a config file, run
```bash
cpconfig
```

### cpsamples
To download the samples of a problem run
```bash
cpsamples <problem>
```

### cptest
To test a solution or set of solutions run
```bash
cptest <problem>/<solution(s)>
```
Pro-tip: you can use glob patterns like ```problem/code*``` or ```problem/*.py```.

### cpsubmit
To submit a solution (only kattis)
```bash
cpsubmit <problem>/<solution(s)>
```
