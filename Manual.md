# Nuclear Reactor Simulator Manual
## Controles
There are several controles to control the reactor:
### Rods
If you raise the rods, the pressure and the temperature will increase. If you lower them, the temperature and pressure will raise less quick, or if you lower the rods for 100%, the temperature will be stable and the pressure will start falling, due to natural pressure loss.
### Turbines
If you raise the turbine power, pressure and temperature will start falling (but they can still raise if the rods are raised) and energy will be generated. The turbine temperature will be raising too. If the turbine power is below 10%, turbine temperature will start falling. The lower the turbine power, the more efficient the turbine temperature will be falling.
### Backup system: Emergency Cooling System
This is a backup system that needs to be purchased with 200 coins. It lowers the temperature with 243°C every second during 4 seconds. It has a cooldown of 1 minute.
### Backup system: Emergency Pressure Relief System
This is a backup system that needs to be purchased with 200 coins. It lowers the pressure with 9.7 bar every second during 4 seconds. It has a cooldown of 1 minute.
## Error panel
The error panel is a usefull item in the simulator that shows you when things are getting dangerous. The meaning of each error can be seen in the list undernead.
### OVERHEAT
Reason: temperature is higher than 1000°C<br>
What you should do: lower the temperature<br>
How to: lower rods, increase turbine power and if possible, activate emergency cooling system.
### CRITICAL OVERHEAT
Reason: temperature is higher than 1300°C<br>
What you should do: really lower the temperature now<br>
How to: lower rods, increase turbine power and if possible, activate emergency cooling system.
### OVERPRESSURE
Reason: pressure is higher than 150 bar<br>
What you should do: lower the pressure<br>
How to: lower rods, increase turbine power and if possible, activate emergency pressure relieve system.
### CRITICAL OVERPRESSURE
Reason: pressure is higher than 175 bar<br>
What you should do: lower the pressure<br>
How to: lower rods, increase turbine power and if possible, activate emergency pressure relieve system.
### TURBINE OVERHEAT
Reason: turbine temperature is higher than 50°C<br>
What you should do: lower the turbine power
### TURBINE CRITICAL
Reason: turbine temperature is higher than 75°C<br>
What you should do: lower the turbine power greatly
### TURBINE NOT FUNCTIONAL
Reason: turbine temperature higher than 100°C<br>
What you should do: shutdown the turbine<br>
How to: drag the turbine power to 0.
### !!!MELTDOWN IMMINENT!!!
Reason: this is the biggest error possible. This means that either the temperature raised beyond 1500°C or that the pressure climbed to above 200 bar. If you don't change, the reactor will meltdown and you will be gameover.<br>
Special: error has larger font than others when active and it triggers a nuclear alarm siren.<br>
What you should do: Immediatly shutdown the reactor<br>
How to: rods to 0%, turbines to 100% and activate the emergency systems.
### MELTDOWN
Reason: the reactor temperature climbed above 2000°C or the pressure climbed to above 250 bar.
What you should do: refresh the page and re-begin playing the game, all your progress is gone.
## Coins
Coins can be spend in the shop. They are obtained when power is generated.
