Name    |IP |Task|  Device   |Name    |IDX |GPIO|	Mac Number
--------|---|----|-----------|--------|----|----|------
ESP-GW  |102|1 |Temp-DS18b20  |DS18 	|800 |14  |5C:CF:7F:41:32:AD
bld:148 |   |4 |Dummy Device  |Fan  	|... |    |5C:CF:7F:41:32:AD
sda-IO4 |   |5 |System Info   |up     |801 |
scl:IO5 |   |6 |System Info 	|ram  	|802 |
.  	    |   |7 |System Info   |load   |803 |	  |
|||||||
SO-RF   |103|1 |Switch input  |Sw1  	|431 |0   |5C:CF:7F:0C:D7:CA
bld:145 |   |3 |System Info 	|ram  	|... |    |5C:CF:7F:0C:D7:CA
.  	    |   |4 |System Info   |up     |436 |	  |
|||||||
SO-FD   |104|1 |Switch input  |Sw1    |421 |0   |5C:CF:7F:81:47:8B
bld:145 |   |3 |System Info   |up     |786 |    |5C:CF:7F:81:47:8B
.  		  |   |4 |System Info 	|ram  	|... |
|||||||
SO-BL   |105|1 |Switch input  |Sw1    |397 |0   |5C:CF:7F:81:4B:C4
bld:145 |   |3 |System Info   |up     |486 |    |5e:cf:7f:81:4b:c4
.  		  |   |4 |System Info 	|ram  	|... |	
|||||||
ESP-2rel|106|1 |Switch input  |Sw1    |    |0   |60:01:94:0E:60:61
.  		  |   |  |System Info 	|     	|    |	  |60:01:94:0E:60:61
|||||||
SO-SL   |107|1 |Switch input  |Sw1    |591 |0   |5C:CF:7F:0C:B1:C0
bld:145 |   |3 |System Info   |up     |592 |	  |5e:cf:7f:0c:b1:c0
.  	    |   |4 |System Info   |ram    |... |	  |
|||||||
SO-4MB  |108|1 |Switch input  |Sw1    |809 |0   |5C:CF:7F:0C:B4:4C
.  	    |   |3 |System Info   |up     |747 |	  |5C:CF:7F:0C:B4:4C
.  	    |   |4 |System Info   |ram    |... |	  |
|||||||
ESP-H801|111|1 |PMExt-Port100 |lamel  |572 |I2C |5C:CF:7F:16:DC:70
bld:147 |   |2 |PMExt-Port101 |lamel= |425 |I2C |5C:CF:7F:16:DC:70
sda-IO3 |   |5 |Analog input  |lux    |537 |ADC |
scl-IO1 |   |6 |System Info   |load   |571 |    |
.       |   |7 |System Info   |up     |480 |	|
.  	|   |8 |System Info   |ram    |750 |	|
.  	|   |9 |Temp/Hum/DHT22|THbox  |583 |5   |
|||||||
ESP-LS  |112|1 |PMExt-Port100 |lamel  |667 |I2C |CC:50:E3:4B:CC:8A
bld:148 |   |2 |PMExt-Port101 |lamel= |749 |I2C |CC:50:E3:4B:CC:8A
sda-IO5 |   |3 |System Info   |up     |... |    |
scl-IO4 |   |4 |System Info   |ram    |... |    |
.       |   |5 |System Info   |load   |... |    |
.       |   |6 |System Info   |rrsi   |... |	|
|||||||
ESP-MCUl|113|1 |System Info   |up     |811 |    |5C:CF:7F:13:8C:E4
bld:mega|   |  |              |       |    |	|5C:CF:7F:13:8C:E4
20191123|
||||||| 
ESP-test|114|1 |System Info   |up     |810 |    |5C:CF:7F:19:68:B7
sda-IO13|   |2 |Light-BH1750  |bh1750 |789 |I2C |5C:CF:7F:19:68:B7
scl-IO12|   |3 |TempHum SI7021|si7021 |760 |I2C |
.  	|   |4 |Analog input  |temp   |798 |ADC |
bld:mega|   |8 |System Info   |ram    |480 |	|
20191208|   |9 |System Info   |rrsi   |750 |	|
.  	    |10|System Info   |load   |... |    |
.  	    |11|System Info   |web    |... |    |
.  	    |12|System Info   |stack  |... |    |
|||||||
ESP-neo1|115|1 |              |       |    |    |A4:CF:12:C9:A0:BD
bld:148 |   |  |            	|     	|    |	  |a4:cf:12:c9:a0:bd
.       |   |  |            	|     	|    |	  |
|||||||
ESP-neo2|116|1 |              |       |    |    |CC:50:E3:7C:EB:93
bld:148 |   |  |            	|     	|    |	  |ce:50:e3:7c:eb:93
.       |   |  |            	|     	|    |	  |
|||||||
SO-POW1 |121|  |Switch        |Sw     |810 |    |5C:CF:7F:92:CC:05
.       |   |  |Current       |Ampere |789 |I2C |5C:CF:7F:92:CC:05
Espurna |   |  |Voltage       |Volt   |760 |I2C |
v 1.13.3|   |  |Active Power	|Watt   |798 |ADC |
.       |   |  |Reactive Power|Watt   |480 |	  |
.       |   |  |Apparent Power|Watt   |750 |	  |
.  	    |   |  |Power factor  |cos-phi|... |    |
.  	    |   |  |Energy        |kWh    |... |    |
|||||||
SO-POW2 |122|  |Switch        |Sw     |731 |    |5C:CF:7F:92:DC:B7
.       |   |  |Current       |Ampere |741 |I2C |5C:CF:7F:92:DC:B7
Espurna |   |  |Voltage       |Volt   |739 |I2C |
v 1.13.3|   |  |Active Power	|Watt   |733 |ADC |
.       |   |  |Reactive Power|Watt   |735 |	  |
.       |   |  |Apparent Power|Watt   |737 |	  |
.  	    |   |  |Power factor  |cos-phi|743 |    |
.  	    |   |  |Energy        |kWh    |745 |    |
|||||||
