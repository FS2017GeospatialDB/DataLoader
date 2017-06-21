# DataLoader
The main script to dump the data into Cassandra cluster

## Prerequisites
* Python 2.7
* A modified version of Google S2 Library (listed below)

## Install
1. Install the basic requirements using `pip install -r requirements.txt` 
2. Get && install the modified S2 library from [here](https://github.com/huhwang/s2-geometry-library)
3. `cp config.yml.example config.yml && vi config.yml` to edit the program behavior

## Usage
`./main.py features.json` 
or
`./main.py file1.json file2.json file3.json ...`
