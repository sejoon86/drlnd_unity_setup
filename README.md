* I am trying to use the Udacity's Unity environment locally in my **offline notebook** (windows 10, 64bit).
* However, I am having some difficulties in doing so :(





The **Tennis.exe** gets executed as shown below. However, the tennis ball just keeps falling down without the paddles moving (since no action is given). 

![Alt text](wontwork.png?raw=true "Optional Title")



After some time, the following error appears. 


![Alt text](wontwork2.png?raw=true "Optional Title")


* I made a conda environment named **drlnd**, and the following is the result of `pip freeze > Requirements.txt`.
* I know there are some differences between the recommended requirements, but I am unsure if this is the problem.

```
absl-py==0.7.1
alabaster==0.7.12
anaconda-client==1.7.2
anaconda-navigator==1.9.6
anaconda-project==0.8.2
asn1crypto==0.24.0
astor==0.7.1
astroid==2.1.0
astropy==3.1
atomicwrites==1.2.1
attrs==18.2.0
Babel==2.6.0
backcall==0.1.0
backports.os==0.1.1
backports.shutil-get-terminal-size==1.0.0
beautifulsoup4==4.6.3
bitarray==0.8.3
bkcharts==0.2
blaze==0.11.3
bleach==3.0.2
bokeh==1.0.2
boto==2.49.0
Bottleneck==1.2.1
certifi==2018.11.29
cffi==1.11.5
chardet==3.0.4
Click==7.0
cloudpickle==0.6.1
clyent==1.2.2
colorama==0.4.1
comtypes==1.1.7
conda-verify==3.1.1
contextlib2==0.5.5
cryptography==2.4.2
cycler==0.10.0
Cython==0.29.2
cytoolz==0.9.0.1
dask==1.0.0
datashape==0.5.4
decorator==4.3.0
defusedxml==0.5.0
distributed==1.25.1
docopt==0.6.2  ############# installed 
docutils==0.14
entrypoints==0.2.3
et-xmlfile==1.0.1
fastcache==1.0.2
filelock==3.0.10
Flask==1.0.2
Flask-Cors==3.0.7
future==0.17.1
gast==0.2.2
gevent==1.3.7
glob2==0.6
greenlet==0.4.15
grpcio==1.20.0    ###### grpcio==1.11.0  would this be a problem? I coudn't install 1.20.0 woudn't get installed. ######
h5py==2.9.0
heapdict==1.0.0
html5lib==1.0.1
idna==2.8
imageio==2.4.1
imagesize==1.1.0
importlib-metadata==0.6
ipykernel==5.1.0    ###### installed as recommended
ipython==7.2.0
ipython-genutils==0.2.0
ipywidgets==7.4.2
isort==4.3.4
itsdangerous==1.1.0
jdcal==1.4
jedi==0.13.2
Jinja2==2.10
jsonschema==2.6.0
jupyter==1.0.0     ########## installed as recommended
jupyter-client==5.2.4
jupyter-console==6.0.0
jupyter-core==4.4.0
jupyterlab==0.35.3
jupyterlab-server==0.2.0
Keras==2.2.4
Keras-Applications==1.0.7
Keras-Preprocessing==1.0.9
keyring==17.0.0
kiwisolver==1.0.1
lazy-object-proxy==1.3.1
libarchive-c==2.8
llvmlite==0.26.0
locket==0.2.0
lxml==4.2.5
Markdown==3.1
MarkupSafe==1.1.0
matplotlib==3.0.2  ############  installed as recommended
mccabe==0.6.1
menuinst==1.4.14
midi==0.2.3
mistune==0.8.4
mkl-fft==1.0.6
mkl-random==1.0.2
mock==2.0.0
more-itertools==4.3.0
mpmath==1.1.0
msgpack==0.5.6
multipledispatch==0.6.0
navigator-updater==0.2.1
nbconvert==5.4.0
nbformat==4.4.0
networkx==2.2
nltk==3.4
nose==1.3.7
notebook==5.7.4
numba==0.41.0
numexpr==2.6.8
numpy==1.16.2    ###### numpy>=1.11.0  no problem here
numpydoc==0.8.0
odo==0.5.1
olefile==0.46
opencv-contrib-python==4.1.0.25
openpyxl==2.5.12
packaging==18.0
pandas==0.23.4  ###### installed as recommended
pandocfilters==1.4.2
parso==0.3.1
partd==0.3.9
path.py==11.5.0
pathlib2==2.3.3
patsy==0.5.1
pbr==5.1.3
pep8==1.7.1
pickleshare==0.7.5
Pillow==6.0.0    ##########  Pillow>=4.2.1 no problem here
pkginfo==1.4.2
pluggy==0.8.0
ply==3.11
prometheus-client==0.5.0
prompt-toolkit==2.0.7
protobuf==3.5.2    ########### no problem here  protobuf==3.5.2
psutil==5.4.8
py==1.7.0
pycodestyle==2.4.0
pycosat==0.6.3
pycparser==2.19
pycrypto==2.6.1
pycurl==7.43.0.2
pyflakes==2.0.0
Pygments==2.3.1
pylint==2.2.2
pyodbc==4.0.25
pyOpenSSL==18.0.0
pyparsing==2.3.0
PySocks==1.6.8
pytest==4.0.2    ########## pytest>=3.2.2 no problem here
pytest-arraydiff==0.3
pytest-astropy==0.5.0
pytest-doctestplus==0.2.0
pytest-openfiles==0.3.1
pytest-remotedata==0.3.1
python-dateutil==2.7.5
pytz==2018.7
PyWavelets==1.0.1
pywin32==223
pywinpty==0.5.5
PyYAML==3.13   ########## installed pyyaml
pyzmq==17.1.2
QtAwesome==0.5.3
qtconsole==4.4.3
QtPy==1.5.2
requests==2.21.0
rope==0.11.0
ruamel-yaml==0.15.46
scikit-image==0.14.1
scikit-learn==0.20.1
scipy==1.2.1  ###### installed as recommended
seaborn==0.9.0
Send2Trash==1.5.0
simplegeneric==0.8.1
singledispatch==3.4.0.3
six==1.12.0
snowballstemmer==1.2.1
sortedcollections==1.0.1
sortedcontainers==2.1.0
Sphinx==1.8.2
sphinxcontrib-websupport==1.1.0
spyder==3.3.2
spyder-kernels==0.3.0
SQLAlchemy==1.2.15
statsmodels==0.9.0
sympy==1.3
tables==3.4.4
tblib==1.3.2
tensorboard==1.13.1
tensorflow==1.13.1   ############## tensorflow==1.7.1 recommended by udacity
tensorflow-estimator==1.13.0
tensorflow-gpu==1.13.1
termcolor==1.1.0
terminado==0.8.1
testpath==0.4.2
toolz==0.9.0
torch==1.2.0    ########### torch==0.4.0   <-- would this be a problem?
torchvision==0.4.0
tornado==5.1.1
tqdm==4.28.1
traitlets==4.3.2
unicodecsv==0.14.1
unityagents==0.4.0
urllib3==1.24.1
wcwidth==0.1.7
webencodings==0.5.1
Werkzeug==0.14.1
widgetsnbextension==3.4.2
win-inet-pton==1.0.1
win-unicode-console==0.5
wincertstore==0.2
wrapt==1.10.11
xlrd==1.2.0
XlsxWriter==1.1.2
xlwings==0.15.1
xlwt==1.3.0
zict==0.1.3
```
