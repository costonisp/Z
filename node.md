Name    |IP |Task|Device|Name   |IDX |GPIO|sda-scl| UDP | Mac Number      |Build
--------|---|----|------|-------|----|----|-------|-----|-----------------|----
ESP-GW  |102|1 |DS18b20 |DS18 	|800 |14  |IO 4-5 |65500|5C:CF:7F:41:32:AD|148
.       |   |4 |Dummy   |Fan  	|... |    |
.       |   |5 |SysInfo |up     |801 |
.       |   |6 |SysInfo |ram  	|802 |
.  	    |   |7 |SysInfo |load   |803 |	  |
|||||||
SO-RF   |103|1 |Switch  |Sw1  	|431 |0   |       |65500|5C:CF:7F:0C:D7:CA|145
.       |   |3 |SysInfo |ram  	|... |    |
.  	    |   |4 |SysInfo |up     |436 |	  |
|||||||
SO-FD   |104|1 |Switch  |Sw1    |421 |0   |       |65500|5C:CF:7F:81:47:8B|145
.       |   |3 |SysInfo |up     |786 |    |
.  		  |   |4 |SysInfo |ram  	|... |
|||||||
SO-BL   |105|1 |Switch  |Sw1    |397 |0   |       |65500|5C:CF:7F:81:4B:C4|145
.       |   |3 |SysInfo |up     |486 |    |
.  		  |   |4 |SysInfo |ram  	|... |	
|||||||
ESP2rel |106|1 |Switch  |Sw1    |    |0   |       |-----|60:01:94:0E:60:61|xxx
.  		  |   |  |SysInfo |     	|    |	  |
|||||||
SO-SL   |107|1 |Switch  |Sw1    |591 |0   |       |65500|5C:CF:7F:0C:B1:C0|145
.       |   |3 |SysInfo |up     |592 |	  |
.  	    |   |4 |SysInfo |ram    |... |	  |
|||||||
SO-4MB  |108|1 |Switch  |Sw1    |809 |0   |       |8266 |5C:CF:7F:0C:B4:4C|148
.  	    |   |3 |SysInfo |up     |747 |	  |
.  	    |   |4 |SysInfo |ram    |... |	  |
|||||||
ESPh801 |111|1 |PME-100 |lamel  |572 |I2C |IO 3-1 |     |5C:CF:7F:16:DC:70|147
.       |   |2 |PME-101 |lamel= |425 |I2C |
.       |   |5 |AnalogIn|lux    |537 |ADC |
.       |   |6 |SysInfo |load   |571 |    |
.       |   |7 |SysInfo |up     |480 |	  |
.  	    |   |8 |SysInfo |ram    |750 |	  |
.  	    |   |9 |DHT22   |THbox  |583 |5   |
|||||||
ESPlamel|112|1 |PME-100 |lamel  |667 |I2C |IO 5-4 |     |CC:50:E3:4B:CC:8A|148
.       |   |2 |PME-101 |lamel= |749 |I2C |
.       |   |3 |SysInfo |up     |... |    |
.       |   |4 |SysInfo |ram    |... |    |
.       |   |5 |SysInfo |load   |... |    |
.       |   |6 |SysInfo |rrsi   |... |	  |
|||||||
ESPmcu1 |113|1 |SysInfo |up     |811 |    |       |8266 |5C:CF:7F:13:8C:E4|mega20191123
.       |   |  |        |       |    |	  |
.       |
.       |
|||||||
ESPtest |114|1 |SysInfo |up     |810 |    |IO13-12|8266 |5C:CF:7F:19:68:B7|mega20191208
.       |   |2 |BH1750  |bh1750 |789 |I2C |
.       |   |3 |SI7021  |si7021 |760 |I2C |
.  	    |   |4 |AnalogIn|temp   |798 |ADC |
.       |   |8 |SysInfo |ram    |480 |
.       |   |9 |SysInfo |rrsi   |750 |
.  	    |   |10|SysInfo |load   |... |
.  	    |   |11|SysInfo |web    |... |
.  	    |   |12|SysInfo |stack  |... |
|||||||
ESPneo1 |115|1 |        |       |    |    |       |8266 |A4:CF:12:C9:A0:BD|mega20191208
.       |   |  |        |     	|    |	  |
.       |   |  |        |     	|    |	  |
|||||||
ESPneo2 |116|1 |        |       |    |    |       |8266 |CC:50:E3:7C:EB:93|mega220191208
.       |   |  |        |     	|    |	  |
.       |   |  |        |     	|    |	  |
|||||||
SO-pow1 |121|  |Switch  |Sw     |810 |    |       | --- |5C:CF:7F:92:CC:05|Espurna1.13.3
.       |   |  |Current |Ampere |789 |I2C |
.       |   |  |Voltage |Volt   |760 |I2C |
.       |   |  |Act Pwr	|Watt   |798 |ADC |
.       |   |  |ReacPwr |Watt   |480 |	  |
.       |   |  |App Pwr |Watt   |750 |	  |
.  	    |   |  |Pwr fact|cos-phi|... |    |
.  	    |   |  |Energy  |kWh    |... |    |
|||||||
SO-pow2 |122|  |Switch  |Sw     |731 |    |       | --- |5C:CF:7F:92:DC:B7|Espurna1.13.3
.       |   |  |Current |Ampere |741 |I2C |
.       |   |  |Voltage |Volt   |739 |I2C |
.       |   |  |Act Pwr	|Watt   |733 |ADC |
.       |   |  |ReacPwr |Watt   |735 |	  |
.       |   |  |App Pwr |Watt   |737 |	  |
.  	    |   |  |Pwr fact|cos-phi|743 |    |
.  	    |   |  |Energy  |kWh    |745 |    |
|||||||
