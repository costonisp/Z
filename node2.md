Name    |mac|Device|Name   |IDX |GPIO|sda-scl| .
--------|---|------|-------|----|----|-------|----
Task    |ip |      |       |IDX |GPIO|sda-scl| ...
ESP-GW  |102|5C:CF:7F:41:32:AD||UDP 65500||Build 148|
1       |   |DS18b20 |DS18 	|800 |14  |IO 4-5 |
4       |   |Dummy   |Fan  	|... |    |
5       |   |SysInfo |up     |801 |
6       |   |SysInfo |ram  	|802 |
7  	    |   |SysInfo |load   |803 |	  |
|||||||
SO-RF   |103|5C:CF:7F:0C:D7:CA||UDP65500||Build 145
1       |   |Switch  |Sw1  	|431 |0   |       |
4  	    |   |SysInfo |up     |436 |	  |
|||||||
SO-FD   |104|5C:CF:7F:81:47:8B||UDP 65500||Build145
1       |   |Switch  |Sw1    |421 |0   |       |
3       |   |SysInfo |up     |786 |    |
|||||||
SO-BL   |105|5C:CF:7F:81:4B:C4||UDP 65500||Build145
1       |   |Switch  |Sw1    |397 |0   |       | 
3       |   |SysInfo |up     |486 |    |
|||||||
ESP2rel |106|60:01:94:0E:60:61||udp 65500||
1       |   |Output  |Relay1 |758 |14  |IO 4-5 |
2  		  |   |Output  |Relay2 |759 |12  |
3       |   |SI7021  |       |642 |    |
5       |   |SysInfo |up     |785 |	  |
|||||||
SO-SL   |107|5C:CF:7F:0C:B1:C0||udp 65500|| 145
1       |   |Switch  |Sw1    |591 |0   |       |
3       |   |SysInfo |up     |592 |	  |
|||||||
SO-4MB  |108|5C:CF:7F:0C:B4:4C||udp 8266||148
1       |   |Switch  |Sw1    |809 |0   |       |
3  	    |   |SysInfo |up     |747 |	  |
|||||||
ESPh801 |111|5C:CF:7F:16:DC:70|147
1       |   |PME-100 |lamel  |572 |I2C |IO 3-1 |
2       |   |PME-101 |lamel= |425 |I2C |
5       |   |AnalogIn|lux    |537 |ADC |
6       |   |SysInfo |load   |571 |    |
7       |   |SysInfo |up     |480 |	  |
8  	    |   |SysInfo |ram    |750 |	  |
9  	    |   |DHT22   |THbox  |583 |5   |
|||||||
ESPlamel|112|CC:50:E3:4B:CC:8A|148
1       |   |PME-100 |lamel  |667 |I2C |IO 5-4 |
2       |   |PME-101 |lamel= |749 |I2C |
3       |   |SysInfo |up     |... |    |
|||||||
ESPmcu1 |113|5C:CF:7F:13:8C:E4|udp 8266||mega20191123
1       |   |SysInfo |up     |811 |    |       |
.       |   |        |       |    |	   |
.       |
|||||||
ESPtest |114|5C:CF:7F:19:68:B7||udp 8366||mega20191208
1       |   |SysInfo |up     |810 |    |IO13-12|
2       |   |BH1750  |bh1750 |789 |I2C |
3       |   |SI7021  |si7021 |760 |I2C |
4  	    |   |AnalogIn|temp   |798 |ADC |
8       |   |SysInfo |ram    |480 |
9       |   |SysInfo |rrsi   |750 |
10 	    |   |SysInfo |load   |... |
11 	    |   |SysInfo |web    |... |
12 	    |   |SysInfo |stack  |... |
|||||||
ESPneo1 |115|A4:CF:12:C9:A0:BD||udp 8266||mega20191208
1       |   |        |      |    |    |       |
.       |   |        |     	|    |	  |
.       |   |        |     	|    |	  |
|||||||
ESPneo2 |116|CC:50:E3:7C:EB:93||udp 8266||mega220191208
1       |   |        |       |    |    |       |
.       |   |        |     	|    |	  |
.       |   |        |     	|    |	  |
|||||||
SO-pow1 |121|5C:CF:7F:92:CC:05|Espurna1.13.3
.       |   |Switch  |Sw     |810 |    |       |
.       |   |Current |Ampere |789 |I2C |
.       |   |Voltage |Volt   |760 |I2C |
.       |   |Act Pwr	|Watt   |798 |ADC |
.       |   |ReacPwr |Watt   |480 |	  |
.       |   |App Pwr |Watt   |750 |	  |
.  	    |   |Pwr fact|cos-phi|... |    |
.  	    |   |Energy  |kWh    |... |    |
|||||||
SO-pow2 |122|5C:CF:7F:92:DC:B7|Espurna1.13.3
.       |   |Switch  |Sw     |731 |    |       |
.       |   |Current |Ampere |741 |I2C |
.       |   |Voltage |Volt   |739 |I2C |
.       |   |Act Pwr |Watt   |733 |ADC |
.       |   |ReacPwr |Watt   |735 |	  |
.       |   |App Pwr |Watt   |737 |	  |
.  	    |   |Pwr fact|cos-phi|743 |    |
.  	    |   |Energy  |kWh    |745 |    |
|||||||
