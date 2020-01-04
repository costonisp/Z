Name task|IP |Device|Name   |IDX |GPIO|sda-scl| UDP |.
--------|---|------|-------|----|----|-------|-----|---
ESP-GW  |mac|5C:CF:7F:41:32:AD|||||Build 148|
1       |102|DS18b20 |DS18 	|800 |14  |IO 4-5 |65500|
4       |   |Dummy   |Fan  	|... |    |
5       |   |SysInfo |up     |801 |
6       |   |SysInfo |ram  	|802 |
7  	    |   |SysInfo |load   |803 |	  |
|||||||
SO-RF   |mac|5C:CF:7F:0C:D7:CA|||||Build 145|
1       |103|Switch  |Sw1  	|431 |0   |       |65500|
4  	    |   |SysInfo |up     |436 |	  |
|||||||
SO-FD   |mac|5C:CF:7F:81:47:8B|145
1       |104|Switch  |Sw1    |421 |0   |       |65500|
3       |   |SysInfo |up     |786 |    |
|||||||
SO-BL   |mac|5C:CF:7F:81:4B:C4|145
1       |105|Switch  |Sw1    |397 |0   |       |65500| 
3       |   |SysInfo |up     |486 |    |
|||||||
ESP2rel |mac|60:01:94:0E:60:61|xxx
1       |106|Output  |Relay1 |758 |14  |IO 4-5 |65500|
2  		  |   |Output  |Relay2 |759 |12  |
3       |   |SI7021  |       |642 |    |
5       |   |SysInfo |up     |785 |	  |
|||||||
SO-SL   |mac|5C:CF:7F:0C:B1:C0|145
1       |107|Switch  |Sw1    |591 |0   |       |65500|
3       |   |SysInfo |up     |592 |	  |
|||||||
SO-4MB  |mac|5C:CF:7F:0C:B4:4C|148
1       |108|Switch  |Sw1    |809 |0   |       |8266 |
3  	    |   |SysInfo |up     |747 |	  |
|||||||
ESPh801 |mac|5C:CF:7F:16:DC:70|147
1       |111|PME-100 |lamel  |572 |I2C |IO 3-1 |     |
2       |   |PME-101 |lamel= |425 |I2C |
5       |   |AnalogIn|lux    |537 |ADC |
6       |   |SysInfo |load   |571 |    |
7       |   |SysInfo |up     |480 |	  |
8  	    |   |SysInfo |ram    |750 |	  |
9  	    |   |DHT22   |THbox  |583 |5   |
|||||||
ESPlamel|mac|CC:50:E3:4B:CC:8A|148
1       |112|PME-100 |lamel  |667 |I2C |IO 5-4 |     |
2       |   |PME-101 |lamel= |749 |I2C |
3       |   |SysInfo |up     |... |    |
|||||||
ESPmcu1 |mac|5C:CF:7F:13:8C:E4|mega20191123
1       |113|SysInfo |up     |811 |    |       |8266 |
.       |   |        |       |    |	   |
.       |
|||||||
ESPtest |mac|5C:CF:7F:19:68:B7|mega20191208
1       |114|SysInfo |up     |810 |    |IO13-12|8266 |
2       |   |BH1750  |bh1750 |789 |I2C |
3       |   |SI7021  |si7021 |760 |I2C |
4  	    |   |AnalogIn|temp   |798 |ADC |
8       |   |SysInfo |ram    |480 |
9       |   |SysInfo |rrsi   |750 |
10 	    |   |SysInfo |load   |... |
11 	    |   |SysInfo |web    |... |
12 	    |   |SysInfo |stack  |... |
|||||||
ESPneo1 |mac|A4:CF:12:C9:A0:BD|mega20191208
1       |115|        |      |    |    |       |8266 |
.       |   |        |     	|    |	  |
.       |   |        |     	|    |	  |
|||||||
ESPneo2 |mac|CC:50:E3:7C:EB:93|mega220191208
1       |116|        |       |    |    |       |8266 |
.       |   |        |     	|    |	  |
.       |   |        |     	|    |	  |
|||||||
SO-pow1 |mac|5C:CF:7F:92:CC:05|Espurna1.13.3
.       |121|Switch  |Sw     |810 |    |       | --- |
.       |   |Current |Ampere |789 |I2C |
.       |   |Voltage |Volt   |760 |I2C |
.       |   |Act Pwr	|Watt   |798 |ADC |
.       |   |ReacPwr |Watt   |480 |	  |
.       |   |App Pwr |Watt   |750 |	  |
.  	    |   |Pwr fact|cos-phi|... |    |
.  	    |   |Energy  |kWh    |... |    |
|||||||
SO-pow2 |mac|5C:CF:7F:92:DC:B7|Espurna1.13.3
.       |122|Switch  |Sw     |731 |    |       | --- |
.       |   |Current |Ampere |741 |I2C |
.       |   |Voltage |Volt   |739 |I2C |
.       |   |Act Pwr	|Watt   |733 |ADC |
.       |   |ReacPwr |Watt   |735 |	  |
.       |   |App Pwr |Watt   |737 |	  |
.  	    |   |Pwr fact|cos-phi|743 |    |
.  	    |   |Energy  |kWh    |745 |    |
|||||||
