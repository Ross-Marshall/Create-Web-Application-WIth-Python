# Create-Web-Application-WIth-Python

before running VM

source ./venv/bin/activate

=================================

sudo apt install python-virtualenv


megazor@m5:/me/code/python/WebApplication/noteapp$ virtualenv
Running virtualenv with interpreter /usr/bin/python2
You must provide a DEST_DIR
Usage: virtualenv.py [OPTIONS] DEST_DIR

Options:
  --version             show program's version number and exit
  -h, --help            show this help message and exit
  -v, --verbose         Increase verbosity.
  -q, --quiet           Decrease verbosity.
  -p PYTHON_EXE, --python=PYTHON_EXE
                        The Python interpreter to use, e.g.,
                        --python=python2.5 will use the python2.5 interpreter
                        to create the new environment.  The default is the
                        python2 interpreter on your path (e.g.
                        /usr/bin/python2)
  --clear               Clear out the non-root install and start from scratch.
  --no-site-packages    DEPRECATED. Retained only for backward compatibility.
                        Not having access to global site-packages is now the
                        default behavior.
  --system-site-packages
                        Give the virtual environment access to the global
                        site-packages.
  --always-copy         Always copy files rather than symlinking.
  --unzip-setuptools    Unzip Setuptools when installing it.
  --relocatable         Make an EXISTING virtualenv environment relocatable.
                        This fixes up scripts and makes all .pth files
                        relative.
  --no-setuptools       Do not install setuptools in the new virtualenv.
  --no-pip              Do not install pip in the new virtualenv.
  --no-wheel            Do not install wheel in the new virtualenv.
  --extra-search-dir=DIR
                        Directory to look for setuptools/pip distributions in.
                        This option can be used multiple times.
  --download            Download preinstalled packages from PyPI.
  --no-download, --never-download
                        Do not download preinstalled packages from PyPI.
  --prompt=PROMPT       Provides an alternative prompt prefix for this
                        environment.
  --setuptools          DEPRECATED. Retained only for backward compatibility.
                        This option has no effect.
  --distribute          DEPRECATED. Retained only for backward compatibility.
                        This option has no effect.
megazor@m5:/me/code/python/WebApplication/noteapp$ virtualenv -p /usr/bin/python2.7 ./venv
Running virtualenv with interpreter /usr/bin/python2.7
New python executable in /me/code/python/WebApplication/noteapp/venv/bin/python2.7
Also creating executable in /me/code/python/WebApplication/noteapp/venv/bin/python
Installing setuptools, pkg_resources, pip, wheel...done.
megazor@m5:/me/code/python/WebApplication/noteapp$ ls
__main__.py  noteapp  venv
megazor@m5:/me/code/python/WebApplication/noteapp$ venv/
bash: venv/: Is a directory
megazor@m5:/me/code/python/WebApplication/noteapp$ sl
bash: sl: command not found
megazor@m5:/me/code/python/WebApplication/noteapp$ ls
__main__.py  noteapp  venv
megazor@m5:/me/code/python/WebApplication/noteapp$ source ./venv/bin/activate
(venv) megazor@m5:/me/code/python/WebApplication/noteapp$ pip install flask
