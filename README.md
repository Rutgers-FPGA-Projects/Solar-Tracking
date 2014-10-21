Solar-Tracking
==============

Our project is basically a solar panel system that will adjust its position to keep the panel  perpendicular to the sun/light source so that the panel generates optimal power. The system will have LDR sensors, each of which will have a light dependent resistance value. When panel is  perpendicular to the light source, the LDR sensors should have the same value. But since the sun move in a hemispherical angle around the panel, one of the sensor’s value will be greater than  then other. This information will go through an ADC and then to the FPGA. The FPGA will have a  control algorithm which will set the position of the servos to keep the LDR’s resistance values  equal, thus keeping the panel perpendicular to the sun/light source. 
