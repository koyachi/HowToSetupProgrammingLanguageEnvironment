# Python

use virtualenv.

```
curl -O http://python-distribute.org/distribute_setup.py
sudo python distribute_setup.py 
sudo easy_install virtualenv
virtualenv ENV
source ENV/bin/activate
pip --version
```

add these lines to .zshrc
```
virtualenv ENV
source ENV/bin/activate
```

## ipython and dependencies
```
pip install readline
pip install nose
pip install pexpect
pip install pyzmq
pip install tornado
pip install ipython
pip install numpy
pip install matplotlib
brew install gfortran
pip install scipy
pip install pandas
```

run ipython notebook
```
ipython notebook
```
open [sample notes](https://github.com/ipython/ipython/tree/master/docs/examples/notebooks).

# TODO:
- virtualenvwrapper
- ipython

# links
- http://www.virtualenv.org/en/latest/
- http://www.pip-installer.org/en/latest/
- http://d.hatena.ne.jp/bojovs/20101011/1286736941
- http://labs.unoh.net/2009/12/2009python.html
- http://penandpants.com/2012/02/24/install-python/
