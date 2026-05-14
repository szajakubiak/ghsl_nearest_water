# GHSL nearest water
Search for nearest water pixel in Global Human Settlement Layer (GHSL) data

## Setup for Windows
1. Install latest Python 3 version from the Microsoft Store.

2. Open command line terminal window from Start menu. Create virtual environment in user's main directory and activate it:
``` bash
cd %HOMEPATH%
python -m venv ghslwatervenv
%HOMEPATH%\ghslwatervenv\Scripts\activate
```

3. Clone this repository and unpack it. In the terminal window change the active directory to the main directory of repository.

4. Install requirements:
``` bash
pip install -r requirements.txt
```

5. Run Jupyter:
``` bash
jupyter lab
```

## Links
[GHS land fraction per pixel](https://human-settlement.emergency.copernicus.eu/ghs_land2022.php)

## TODO
* Convert land fraction dataset into water map
