# MS5440-CM
Arduino UNO program for MS5440-CM barometric and temperature sensor.<br>
The sensor is produced by Measurement Specialties.<br>
Temperature accuracy: + /- 0.8 C , Barometric pressure : + /- 1 hPa<br>
Output on serial port every 5 seconds, 9600 bps.<br>
<br>
PINS:
<br>
VCC -----------------> 3.3v<br>
GND ---------------- > GND<br>
DIN (MOSI) ----------> pin (11)<br>
DOUT (MISO) ---------> pin (12)<br>
SCLK ----------------> pin (13)<br>
MCLK ----------------> pin (9)<br>
<br>
Output of program:<br>
************************************<br>
Absolute Pressure =    978 mbar<br>
Sea-level Pressure =    992.27 mbar<br>
Temperature = 21.80 C<br>
************************************<br>
<br>
![alt tag](https://github.com/HyperDevil/MS5440-CM/blob/master/sensor.jpg?raw=true)
