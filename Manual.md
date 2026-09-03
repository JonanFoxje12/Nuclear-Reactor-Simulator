# Nuclear Reactor Simulator Manual
## Controles
There are several controles to control the reactor:
### Rods
If you raise the rods, the pressure and the temperature will increase. If you lower them, the temperature and pressure will raise less quick, or if you lower the rods for 100%, the temperature will be stable and the pressure will start falling, due to natural pressure loss.
### Turbines
If you raise the turbine power, pressure and temperature will start falling (but they can still raise if the rods are raised) and energy will be generated. The turbine temperature will be raising too. If the turbine power is below 10%, turbine temperature will start falling. The lower the turbine power, the more efficient the turbine temperature will be falling.
### Backup system: Emergency Cooling System
This is a backup system that needs to be purchased in the shop. To buy for example the level 2 ECS, you need level 1 ECS too. The system has a cooldown of 5 minutes and is active during 4 seconds. In the table below is shown how much the ECS will lower the temperature and how much it costs:
| Required item | Cost | Temperature decrease per second | Total temperature decrease|
|---------------|------|---------------------------------|---------------------------|
| ECS level 1   | 200  | 126°C                           | 504°C                     |
| ECS level 2   | 300  | 243°C                           | 972°C                     |
| ECS level 3   | 500  | 512°C                           | 2048°C                    |
### Backup system: Emergency Pressure Relief System
This is a backup system that needs to be purchased in the shop. To buy for example the level 2 EPRS, you need level 1 EPRS too. The system has a cooldown of 5 minutes and is active during 4 seconds. In the table below is shown how much the EPRS will lower the temperature and how much it costs:
| Required item | Cost | Pressure decrease per second    | Total pressure decrease   |
|---------------|------|---------------------------------|---------------------------|
| EPRS level 1  | 200  | 9.7 bar                         | 38.8 bar                  |
| EPRS level 2  | 300  | 14.6 bar                        | 54.8 bar                  |
| EPRS level 3  | 500  | 26.3 bar                        | 105.2 bar                 |
### SCRAM
The SCRAM button is the emergency shutdown and can be purchased in the shop for 1000 coins. **Note that <ins>EVERY TIME YOU USE THE SCRAM</ins> you pay 200 coins, <ins>if you don't have 200 coins, you can't use the SCRAM</ins>**. The SCRAM immediatly shutsdown the reactor, but locks the rods at 100% and the turbines and at 0%. After having used the SCRAM, you can restart the reactor. This takes 30 minutes, this is why the SCRAM should only be used in case of absolute emergency.

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
Reason: turbine temperature is higher than 400°C<br>
What you should do: lower the turbine power
### TURBINE CRITICAL
Reason: turbine temperature is higher than 450°C<br>
What you should do: lower the turbine power greatly
### TURBINE NOT FUNCTIONAL
Reason: turbine temperature higher than 500°C<br>
What you should do: shutdown the turbine<br>
How to: drag the turbine power to 0.
### !!!MELTDOWN IMMINENT!!!
Reason: this is the biggest error possible. This means that either the temperature raised beyond 1500°C or that the pressure climbed to above 200 bar. If you don't change, the reactor will meltdown and you will be gameover.<br>
Special: error has larger font than others when active and it triggers a nuclear alarm siren.<br>
What you should do: Immediatly shutdown the reactor<br>
How to: rods to 0%, turbines to 100% and activate the emergency systems.
### MELTDOWN
Reason: the reactor temperature climbed above 2000°C or the pressure climbed to above 250 bar. The reactor is gone.
What you should do: close and reopen the page and re-begin playing the game, all your progress is gone.
## Other
### Coins
Coins can be spent in the shop. They are obtained when power is generated.
