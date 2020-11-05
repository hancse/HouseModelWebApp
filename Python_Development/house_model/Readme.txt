#-----------------------

Run.py : define a number of Simulation days and call the calculation model.

house.py : diffirential equation of the house model, return indoor,walls temperature and energy consumption

internal_heat_gain.py : Create an internal heat profile inside the house (ex: heat generated from equipment and people inside the house)

parameters.py : define house size, orientation, ventilation, insluation thickness, window size, ...

qsun.py: function to calculate solar irradiation on an incline surface

Total_Irrad.py: use qsun.py for calculating solar irradiation from different angles (ex: E,SE,W,...) from the weather data file --> use weather API instead.

Temperature_SP.py: Define temperature SP profile (Thermostat setting.)

