<h1 align="center">Fundamentals of Artificial Intelligence</h1>

## Hit the ground running

``` bash
# clone repository
git clone https://github.com/SkalskiP/ImaBoss.git

# navigate to main directory
cd ImaBoss

# set up and activate python environment
apt-get install python3-venv
python3 -m venv .env
source .env/bin/activate

# install all required packages
pip install -r requirements.txt
```

## Data Description

* ```IAPS.csv``` - information about the emotional characteristics of each image (valence and arousal)
* ```IADS2.csv``` - information about the emotional features of each sound (valence and arousal)
* ```NEO-FFI.txt``` - personality questionnaire results (not available for people in the first week of the survey)

## Useful links

1. [PSI-Exp-2019 Dropbox][1]
2. [Open Signals File Formats specification][2]
3. [Analyzing a Discrete Heart Rate Signal Using Python – Part 1][3]

[1]: https://www.dropbox.com/sh/s3jhgxe13e8f9jw/AADko9DkyvlCDqhekWvMlUOva?dl=0
[2]: http://bitalino.com/datasheets/OpenSignals_File_Formats.pdf
[3]: http://www.paulvangent.com/2016/03/15/analyzing-a-discrete-heart-rate-signal-using-python-part-1/
