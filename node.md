Name    |IP |Task|  Device   |Name    |IDX |GPIO|	Number
--------|---|----|-----------|--------|----|----|------
ESP-GW  |102|1 |Temp-DS18b20  |DS18 	|800 |14  |2
sda-IO4 |   |4 |Dummy Device  |Fan  	|... |
scl-IO5 |   |5 |System Info   |up     |801 |
bld:148 |   |6 |System Info 	|ram  	|802 |
.  	    |   |7 |System Info   |load   |803 |	   |
|||||||
SO-RF   |103|1 |Switch input  |Sw1  	|431 |0   |3
.  		  |   |3 |System Info 	|ram  	|... |
.  	    |   |4 |System Info   |up     |436 |	   |
|||||||
SO-FD   |104|1 |Switch input  |Sw1    |421 |0   |4
.       |   |3 |System Info   |up     |786 |
.  		  |   |4 |System Info 	|ram  	|... |
|||||||
SO-BL   |105|1 |Switch input  |Sw1    |397 |0   |5
.       |   |3 |System Info   |up     |486 |
.  		  |   |4 |System Info 	|ram  	|... |	
|||||||
SO-2rel |106|1 |Switch input  |Sw1    |    |0   |6
|||||||
|||||||
SO-SL   |107|1 |Switch input  |Sw1    |591 |0   |7
.  	    |   |3 |System Info   |up     |592 |	   |
.  	    |   |4 |System Info   |ram    |... |	   |
|||||||
SO-4MB  |108|1 |Switch input  |Sw1    |809 |0   |8
.  	    |   |3 |System Info   |up     |747 |	   |
.  	    |   |4 |System Info   |ram    |... |	   |
|||||||
ESP-H801|111|1 |PMExt-Port100 |lamel  |572 |I2C |11
sda-IO3 |   |2 |PMExt-Port101 |lamel= |425 |I2C |
scl-IO1 |   |5 |Analog input  |lux    |537 |ADC |
.  		  |   |6 |System Info   |load 	|571 |
bld:147 |   |7 |System Info   |up     |480 |	   |
.  	    |   |8 |System Info   |ram    |750 |	   |
.  	    |   |9 |Temp/Hum/DHT22|THbox  |583 |5   |
|||||||
ESP-LS  |112|1 |PMExt-Port100 |lamel  |667 |I2C |12
sda-IO5 |   |2 |PMExt-Port101 |lamel= |749 |I2C |
scl-IO4 |   |3 |System Info   |up     |... |    |
.  		  |   |4 |System Info 	|ram  	|... |
bld:148 |   |5 |System Info   |load   |... |	   |
.  	    |   |6 |System Info   |rrsi   |... |	   |
|||||||
ESP-MCU |114|1 |System Info   |up     |810 |    |14
sda-IO13|   |2 |Light-BH1750  |bh1750 |789 |I2C |
scl-IO12|   |3 |Analog input  |si7021 |760 |I2C |
.  		  |   |4 |System Info 	|temp   |798 |ADC
bld:mega|   |8 |System Info   |ram    |480 |	   |
20191208|   |9 |System Info   |rrsi   |750 |	   |
.  	    |   |10|Temp/Hum/DHT22|load   |... |    |
.  	    |   |11|Temp/Hum/DHT22|web    |... |    |
.  	    |   |12|Temp/Hum/DHT22|stack  |... |    |
|||||||
