# 1. Install python3

To check whether you have python3 installed in your system use:

```
$ python3 --version
```

If that fails, it is most likely python3 isn't installed, but python2 is, in which case this should tell you the the
version you have:

```
$ python --version
```

If python3 is not installed on your system, follow the instructions here:
http://python-guide-pt-br.readthedocs.io/en/latest/starting/installation/

# Install XCode developer tools

```
$ sudo xcode-select --install
```

# Create a virtualenv and install dependencies

```
$ virtualenv --python=`which python3` interview.venv
$ source interview.venv/bin/activate
$ pip install -r requirements.txt
```
The `requirements.txt` mentioned is the one in this repo.

After that is installed you are good to go.
