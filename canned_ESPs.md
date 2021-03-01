
# What are the default ESP settings in the Ash3d GUI? 

Many people ask what are the values of inputs that are set automatically within the Ash3d GUI.  Some of these are explained in the Users Guide (Mastin et al., 2021), but they can be hard to find.  Here is a rundown of the key parameters and how they are derived: 


## The Total grain-size distribution (TGSD)  
The TGSD below is based on a simplification of the Mount St. Helens TGSD, in which particles larger than 2 mm in diameter are consolidated into the 2mm size bin.  Fine ash is represented as aggregates having a density of 600 kg/m2 and size distribution that has been found to adequately reproduce the distribution of deposits at Mount St. Helens (Mastin et al. 2016).  the last five rows in the table below are aggregates.

|Diameter (mm)   |mass fraction   |density (kg/m3)|shape factor F|
|----------------|----------------|---------------|--------------|
| 2              | 0.06118        |  800          |  0.044       |
| 1              | 0.07098        |  1040         |  0.044       |
| 0.5            | 0.22701        |  1280         |  0.044       |
| 0.25           | 0.21868        |  1520         |  0.044       |
| 0.1768         | 0.05362        |  1640         |  0.044       |
| 0.125          | 0.04039        |  1760         |  0.044       |
| 0.088          | 0.02814        |  1800         |  0.044       |
| 0.2176         | 0.018          |  600          |  0.044       |
| 0.2031         | 0.072          |  600          |  1           |
| 0.1895         | 0.12           |  600          |  1           |
| 0.1768         | 0.072          |  600          |  1           |
| 0.1649         | 0.018          |  600          |  1           |


## References:
Mastin LG, Van Eaton AR, Durant AJ (2016) Adjusting particle-size distributions to account for aggregation in tephra-deposit model forecasts. Atmos. Chem. Phys. 16(14):9399-9420
