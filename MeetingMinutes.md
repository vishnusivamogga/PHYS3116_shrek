
# Week 2
Vish generated plots for Energy and Angular momentum using data Galpy. After Energy and Angular momentum was plotted, an initial cut by figuring that the retrograde GCs and higher energies are more likely to be accreted GCs. This cut revealed around 42 GCs excluding some clear outliers which is our initial estimate for the accreted GCs
## Sarv
### Next week Agenda
Make Age-Metalicity plot
From this try find a cut to using research
also compare with the accreted GCs foundin Vish's plot
lines of code
import pandas as pd import matplotlib.pyplot as plt
harrisP1 = pd.read_csv("HarrisPartI.csv")
harrisP3 = pd.read_csv("HarrisPartIII.csv")
Krause = pd.read_csv("Krause21.csv")
VandenBerg = pd.read_csv("vandenBerg_table2.csv")
Krause.plot(kind = 'scatter', x ='FeH',y='Age')
VandenBerg.plot(kind = 'scatter', x ='FeH',y='Age')
### Vish

