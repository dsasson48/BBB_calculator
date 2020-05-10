# BBB_calculator

Implements the blood brain barrier score described in the following paper

J. Med. Chem. 2019, 62, 21, 9824-9836
https://doi.org/10.1021/acs.jmedchem.9b01220

## Install

```
pip install BBB_calculator
```

## Use

```
from BBB_calculator import BBB_score

score = BBB_score(1, 20, 300.29, 1, 7, 122.46, 2.86)
print(score)
# Prints: 1.815645...
```
