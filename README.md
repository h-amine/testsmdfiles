# 							Python Test & Validation Scripts

This repository is a project encapsulating a variety of python scripts enabling web based jobs automation.
For the time being only one directory exists: **_selenium_scripts_**, which contains a bunch of scripts intended to test the reports generated from SECnology.

## selenium_scripts
The following script were implimented using Python 3.6.
Before running the below scripts, make sure the following python modules are well installed:

```
 argparse			 pip install argparse
 pathlib (libpath2)	 	pip install pathlib
 selenium			 pip install selenium
```

### explore_dir_open_reports.py
This script opens a list of reports previously generated from SECnology and dumps the Chrome browser console output in a specific output file.
The user is able to manipulate this script using the below options:

- -c, --chromepath		:				Path to the chromedriver executable file.
- -r, --reports			:				Path to the reports' directory
- -V, --VerSec			:				SECnology version
- [-v], [--verbosity]	:				Verbosity level: OFF, SEVERE, WARNING, INFO, DEBUG, ALL
- [-t], [--time]		:				Time to close the chrome browser window
- [-h], [--help]		:			Display help menu