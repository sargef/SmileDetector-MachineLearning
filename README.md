# Smile Detector / Machine Learning

## Import Libraries

## Copy the following libraries into a notepad file and save as; libraries.yml

name: libraries
channels:
- menpo
- conda-forge
- peterjc123
- defaults
dependencies:
- ffmpeg=3.2.4=1
- freetype=2.7=vc14_1
- imageio=2.2.0=py35_0
- libtiff=4.0.6=vc14_7
- olefile=0.44=py35_0
- pillow=4.2.1=py35_0
- vc=14=0
- alabaster=0.7.10=py35_0
- astroid=1.5.3=py35_0
- babel=2.5.0=py35_0
- bleach=1.5.0=py35_0
- certifi=2016.2.28=py35_0
- cffi=1.10.0=py35_0
- chardet=3.0.4=py35_0
- colorama=0.3.9=py35_0
- decorator=4.1.2=py35_0
- docutils=0.14=py35_0
- entrypoints=0.2.3=py35_0
- html5lib=0.9999999=py35_0
- icu=57.1=vc14_0
- imagesize=0.7.1=py35_0
- ipykernel=4.6.1=py35_0
- ipython=6.1.0=py35_0
- ipython_genutils=0.2.0=py35_0
- isort=4.2.15=py35_0
- jedi=0.10.2=py35_2
- jinja2=2.9.6=py35_0
- jpeg=9b=vc14_0
- jsonschema=2.6.0=py35_0
- jupyter_client=5.1.0=py35_0
- jupyter_core=4.3.0=py35_0
- lazy-object-proxy=1.3.1=py35_0
- libpng=1.6.30=vc14_1
- markupsafe=1.0=py35_0
- mistune=0.7.4=py35_0
- mkl=2017.0.3=0
- nbconvert=5.2.1=py35_0
- nbformat=4.4.0=py35_0
- numpy=1.13.1=py35_0
- numpydoc=0.7.0=py35_0
- openssl=1.0.2l=vc14_0
- pandocfilters=1.4.2=py35_0
- path.py=10.3.1=py35_0
- pickleshare=0.7.4=py35_0
- pip=9.0.1=py35_1
- prompt_toolkit=1.0.15=py35_0
- psutil=5.2.2=py35_0
- pycodestyle=2.3.1=py35_0
- pycparser=2.18=py35_0
- pyflakes=1.6.0=py35_0
- pygments=2.2.0=py35_0
- pylint=1.7.2=py35_0
- pyqt=5.6.0=py35_2
- python=3.5.4=0
- python-dateutil=2.6.1=py35_0
- pytz=2017.2=py35_0
- pyzmq=16.0.2=py35_0
- qt=5.6.2=vc14_6
- qtawesome=0.4.4=py35_0
- qtconsole=4.3.1=py35_0
- qtpy=1.3.1=py35_0
- requests=2.14.2=py35_0
- rope=0.9.4=py35_1
- setuptools=36.4.0=py35_1
- simplegeneric=0.8.1=py35_1
- singledispatch=3.4.0.3=py35_0
- sip=4.18=py35_0
- six=1.10.0=py35_1
- snowballstemmer=1.2.1=py35_0
- sphinx=1.6.3=py35_0
- sphinxcontrib=1.0=py35_0
- sphinxcontrib-websupport=1.0.1=py35_0
- spyder=3.2.3=py35_0
- testpath=0.3.1=py35_0
- tornado=4.5.2=py35_0
- traitlets=4.3.2=py35_0
- vs2015_runtime=14.0.25420=0
- wcwidth=0.1.7=py35_0
- wheel=0.29.0=py35_0
- win_unicode_console=0.5=py35_0
- wincertstore=0.2=py35_0
- wrapt=1.10.11=py35_0
- zlib=1.2.11=vc14_0
- opencv3=3.1.0=py35_0
- pytorch torchvision cudatoolkit=9.0 -c pytorch
- pip:
  - ipython-genutils==0.2.0
  - jupyter-client==5.1.0
  - jupyter-core==4.3.0
  - prompt-toolkit==1.0.15
  - pyyaml==3.12
  - rope-py3k==0.9.4.post1
  - torch==0.1.12
  - torchvision==0.1.9
  - win-unicode-console==0.5


## cd into folder where above libraries.yml file exists once you have saved it, and run this code: 

## conda env create -f libraries.yml

Once downloaded all libaries, open Anaconda platform; libaries from toolbar or programs list and then open Spyder or atom etc, whichever you prefer as your ide.

<img src="https://s3-eu-west-1.amazonaws.com/website38/AnacondaCapture.png" width="1250px">

Then run this code in your terminal: #C:/YOUR FOLDER LOCATION/ python smile.py

