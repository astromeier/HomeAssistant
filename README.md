# HomeAssistant
Astromeier's HomeAssistant configuration

A snapshot of my actual HomeAssistant configuration

HA is installed on an Odroid C2 running an Ubuntu 18.04 small installation

HA is used to control an old long-distance heating station.
The control valve is a motor driven proportional valve with a plus/minus ac driven motor.
The motor has two phase wires for plus and minus direction and a common back-phase.
These two directions are switched by relays - controlled by two thermostat instances for plus and minus direction. 
The latter is controlled by a thermostat in a/c configuration.
The thermostat switches the relays for 1 second, see switches.yaml.
Temperatures are measured by 1-wire Dallas DS18N20 sensors.
Outside ambient temperatures comes from Dark Sky weather service.
A Volkszaehler instance is also running at the odroid to sensor the electrical energy consumpion.
The Volkszaehler frontend and my router frontend are displaed as iframes.

Sorry for the comments in german....
