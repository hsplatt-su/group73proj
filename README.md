# group73proj
Phil McKnight and Harry Platt github repository

import pandas as pd 
import numpy as np 

import warnings 
warnings.filterwarnings('ignore')

under_pressure=pd.read_csv('Undder Pressure .csv')




under_pressure.sample(1)
if under_pressure.iloc[1]['pressure_dropbacks'] > under_pressure.iloc[2]['pressure_dropbacks']:
    point = point + 1
    print("Player 1 is better than player two")
    print("Point:", point)
else:
    print("Player 2 is better than player one")
    
    
    
    
    point = 0

if under_pressure.iloc[1]['pressure_interceptions'] > under_pressure.iloc[2]['pressure_interceptions']:
    point = point + 1
    print("2 is better than 1")
    print("Point:", point)
else:
    print("nah")
