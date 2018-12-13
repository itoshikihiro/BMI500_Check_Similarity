# de-id
Perl and Python code for de-identifying electronic medical records
# Prerequisites
## Python
* Python 3.5.2

# Running insturctions
## Python Code
### De-identification (AGE)
1- Change to the python directory

2- run ```python deid_Age_Parisa.py id.text age.phi```

3- run ```python deid_Location_Parisa.py id.text location.phi```

4- run ```python deid_Date_Parisa.py id.text date.phi```

In which:

* ```id.text``` contains Patient Notes.
* ```age.phi``` is the output file that will be created.
### Stats
1- change to the python directory

2- run ```python stats.py id.deid id-phi.phrase age.phi ```

3- run ```python stats.py id.deid id-phi.phrase location.phi ```

4- run ```python stats.py id.deid id-phi.phrase date.phi ```

In which:

* ```id.deid``` is the gold standard that is category-blind.
* ```id-phi.phrase``` is the gold standard with the categories included.
* ```age.phi``` is the test file that the stats is run on.
* ```location.phi``` is the test file that the stats is run on.
* ```date.phi``` is the test file that the stats is run on.
