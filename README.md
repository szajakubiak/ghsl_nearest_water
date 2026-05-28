# GHSL nearest water
Search for nearest water pixel in Global Human Settlement Layer (GHSL) data

## Setup
### Windows
1. Create and activate virtual environment
``` bash
cd %HOMEPATH%
python -m venv ghslwatervenv
%HOMEPATH%\ghslwatervenv\Scripts\activate
```

### Linux
1. Create and activate virtual environment
``` bash
cd ~
python3 -m venv ghslwatervenv
source ~/ghslwatervenv/bin/activate
```

### Common for Windows and Linux

2. Clone repository and go the main directory in the terminal window.

3. Install requirements
``` bash
pip install -r requirements.txt
```

4. Run Jupyter
``` bash
jupyter lab
```

## Links
[GHS land fraction per pixel](https://human-settlement.emergency.copernicus.eu/ghs_land2022.php)

## TODO
* Write script to calculate distance to water pixel from defined location
