# Python Practice

https://www.python.org

https://github.com/python/cpython

## Practice Reference

[PIP Practice](https://github.com/mrhuangyuhui/practice-manual/blob/master/pip-practice.md)

[Virtualenv Practice](https://github.com/mrhuangyuhui/practice-manual/blob/master/virtualenv-practice.md)

[Pyenv Practice](https://github.com/mrhuangyuhui/practice-manual/blob/master/pyenv-practice.md)

## Installation

### [pyenv](https://github.com/pyenv/pyenv) (Recommended)

### CentOS 7

Prerequisites
```
$ yum group install 'Development Tools' -y
$ yum install zlib-devel bzip2-devel openssl-devel ncurses-devel readline-devel sqlite-devel -y
```
[Downloads](https://www.python.org/downloads/)

Build
```
$ ./configure --prefix=/usr/local/Python/Python-3.6.2/
$ make
$ make test
$ make install
```

Link (For version management)
```
$ cd /usr/local/Python/
$ ln -s Python-3.6.2/ default
```

ENV
```
$ echo 'export PATH=/usr/local/Python/default/bin:$PATH' >> ~/.bash_profile
$ source ~/.bash_profile
```

Verifying
```
$ python3 -V
```

- Ubuntu 


## [Documentation](https://www.python.org/doc/)

### [Python 3](https://docs.python.org/3/)

[The Python Standard Library](https://docs.python.org/3/library/index.html)

[Search page](https://docs.python.org/3/search.html)

[Global Module Index](https://docs.python.org/3/py-modindex.html)

[General Index](https://docs.python.org/3/genindex.html)

#### String

[String Methods](https://docs.python.org/3/library/stdtypes.html#string-methods)

[Format examples](https://docs.python.org/3/library/string.html#format-examples)
