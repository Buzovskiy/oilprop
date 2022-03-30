# Oil properties

A program for calculation of thermal physics and thermodynamics properties of oil

## Install
```
pip install oilprop==0.0.1
```

## Example
Get oil volumetric thermal expansion coefficient for oil with density **rho**
```python
from oilprop.volumetric_thermal_expansion_coefficient import volumetric_thermal_expansion_coefficient as av

print(av(rho=800))  # 0.000937
```