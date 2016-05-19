# RHD

A module for reading Intan RHD2000 files (*.rhd).

Code written by  Michael Gibson 17 July 2015

Module-ified by Kyler Brown, 2016.


## installation

    git clone https://github.com/kylerbrown/rhd.git
    cd rhd
    python setup.py install

## usage

    import rhd
    rhd.read_data("file.rhd")
