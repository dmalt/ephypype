# Description

Neuropycon package of functions for electrophysiology analysis, can be used from
graphpype and nipype


# Documentation

https://neuropycon.github.io/neuropycon_doc/ephypype.html


# Installation

## Requirements
Up to now ephypype works only with python2; python3 compatibility is planned for later releases

* numpy
* scikit-learn
* mne
* nipype
* graphpype

## Install package
### Install ephypype
```bash
git clone https://github.com/neuropycon/ephypype.git
cd ephypype
sudo python setup.py develop
cd ..

```
### Install graphpype
```bash
git clone https://github.com/neuropycon/graphpype.git
cd graphpype
pip install .
cd ..
```

## Software

### Freesurfer

1. Download Freesurfer sotware:

https://surfer.nmr.mgh.harvard.edu/fswiki/DownloadAndInstall

2. Follow the Installation instructions

https://surfer.nmr.mgh.harvard.edu/fswiki/LinuxInstall


### MNE

1. Download MNE sotware:

http://martinos.org/mne/dev/install_mne_c.html
