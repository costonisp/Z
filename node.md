Name    |IP |Task|  Device   |Name    |IDX |GPIO|SDA|SCL| Mac Number      |Build
--------|---|----|-----------|--------|----|----|   |   |-----------------|---
ESP-GW  |102|1 |Temp-DS18b20  |DS18 	|800 |14  |IO4|IO5|5C:CF:7F:41:32:AD|Build 148
.       |   |4 |Dummy Device  |Fan  	|... |    |
.       |   |5 |System Info   |up     |801 |
.       |   |6 |System Info 	|ram  	|802 |
.  	    |   |7 |System Info   |load   |803 |	  |
|||||||
SO-RF   |103|1 |Switch input  |Sw1  	|431 |0   |   |   |5C:CF:7F:0C:D7:CA|Build 145
.       |   |3 |System Info 	|ram  	|... |    |
.  	    |   |4 |System Info   |up     |436 |	  |
|||||||
SO-FD   |104|1 |Switch input  |Sw1    |421 |0   |   |   |5C:CF:7F:81:47:8B|Build 145
.       |   |3 |System Info   |up     |786 |    |
.  		  |   |4 |System Info 	|ram  	|... |
|||||||
SO-BL   |105|1 |Switch input  |Sw1    |397 |0   |   |   |5C:CF:7F:81:4B:C4|Build 145
.       |   |3 |System Info   |up     |486 |    |
.  		  |   |4 |System Info 	|ram  	|... |	
|||||||
ESP-2rel|106|1 |Switch input  |Sw1    |    |0   |   |   |60:01:94:0E:60:61|Build x
.  		  |   |  |System Info 	|     	|    |	  |
|||||||
SO-SL   |107|1 |Switch input  |Sw1    |591 |0   |   |   |5C:CF:7F:0C:B1:C0|Build 145
.       |   |3 |System Info   |up     |592 |	  |
.  	    |   |4 |System Info   |ram    |... |	  |
|||||||
SO-4MB  |108|1 |Switch input  |Sw1    |809 |0   |   |   |5C:CF:7F:0C:B4:4C|Build 148
.  	    |   |3 |System Info   |up     |747 |	  |
.  	    |   |4 |System Info   |ram    |... |	  |
|||||||
ESP-H801|111|1 |PMExt-Port100 |lamel  |572 |I2C |IO3|IO1|5C:CF:7F:16:DC:70|Build 147
.       |   |2 |PMExt-Port101 |lamel= |425 |I2C |
.       |   |5 |Analog input  |lux    |537 |ADC |
.       |   |6 |System Info   |load   |571 |    |
.       |   |7 |System Info   |up     |480 |	  |
.  	    |   |8 |System Info   |ram    |750 |	  |
.  	    |   |9 |Temp/Hum/DHT22|THbox  |583 |5   |
|||||||
ESP-LS  |112|1 |PMExt-Port100 |lamel  |667 |I2C |IO5|IO4|CC:50:E3:4B:CC:8A|Build 148
.       |   |2 |PMExt-Port101 |lamel= |749 |I2C |
.       |   |3 |System Info   |up     |... |    |
.       |   |4 |System Info   |ram    |... |    |
.       |   |5 |System Info   |load   |... |    |
.       |   |6 |System Info   |rrsi   |... |	  |
|||||||
ESP-MCUl|113|1 |System Info   |up     |811 |    |   |   |5C:CF:7F:13:8C:E4|Bld mega20191123
.       |   |  |              |       |    |	  |
.       |
.       |
|||||||
ESP-test|114|1 |System Info   |up     |810 |    |IO13|IO12|5C:CF:7F:19:68:B7|:Bld mega20191208
.       |   |2 |Light-BH1750  |bh1750 |789 |I2C |
.       |   |3 |TempHum SI7021|si7021 |760 |I2C |
.  	    |   |4 |Analog input  |temp   |798 |ADC |
.       |   |8 |System Info   |ram    |480 |
.       |   |9 |System Info   |rrsi   |750 |
.  	    |   |10|System Info   |load   |... |
.  	    |   |11|System Info   |web    |... |
.  	    |   |12|System Info   |stack  |... |
|||||||
ESP-neo1|115|1 |              |       |    |    |   |   |A4:CF:12:C9:A0:BD|Bld 148
.       |   |  |            	|     	|    |	  |
.       |   |  |            	|     	|    |	  |
|||||||
ESP-neo2|116|1 |              |       |    |    |   |   |CC:50:E3:7C:EB:93|Build 148
.       |   |  |            	|     	|    |	  |
.       |   |  |            	|     	|    |	  |
|||||||
SO-POW1 |121|  |Switch        |Sw     |810 |    |   |   |5C:CF:7F:92:CC:05|Espurna 1.13.3
.       |   |  |Current       |Ampere |789 |I2C |
.       |   |  |Voltage       |Volt   |760 |I2C |
.       |   |  |Active Power	|Watt   |798 |ADC |
.       |   |  |Reactive Power|Watt   |480 |	  |
.       |   |  |Apparent Power|Watt   |750 |	  |
.  	    |   |  |Power factor  |cos-phi|... |    |
.  	    |   |  |Energy        |kWh    |... |    |
|||||||
SO-POW2 |122|  |Switch        |Sw     |731 |    |   |   |5C:CF:7F:92:DC:B7|Espurna 1.13.3
.       |   |  |Current       |Ampere |741 |I2C |
.       |   |  |Voltage       |Volt   |739 |I2C |
.       |   |  |Active Power	|Watt   |733 |ADC |
.       |   |  |Reactive Power|Watt   |735 |	  |
.       |   |  |Apparent Power|Watt   |737 |	  |
.  	    |   |  |Power factor  |cos-phi|743 |    |
.  	    |   |  |Energy        |kWh    |745 |    |
|||||||
