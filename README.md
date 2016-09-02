# 3DPrint
Machine setting for 3D Printers  

This repository it's made for [**Optimus**](http://goo.gl/feKXvQ)'s printers.  

### Layers height:  
Formula:  
`nozzle / 2` max  
`nozzle / 4` min  
Steps resolution: 0.05  

### Speed settings:  
1. **Plastink**
  * PLA: 35 – 80 mm/sec  
  * ABS: 35 mm/sec  , you can rise up to 50mm/sec after 10 layers.
2. --------

### Bed guide line:  
* **ABS**: no problem with default setting.  
* **PLA**: 40° with hair spray remain the best solution ( default setting ). If you have not hair spray, you must set 70° on the bed.  

### Fan guide line:
For **PLA** prefer set the speed layers by layers on machine, Cura does not work good at free wheel....  

Remember Gcode's setting, useful for Cura 15.x.x:  
* fan on: M106 S[0-255]
* fan off: M107  

**ABS** don't need fan, only in rare cases.  

##Cura 2.x.x
It's available for download in this folder, profile and machine setting.  
Locate the files:
* C:\Program Files\Cura 2.1\resources\machine
* C:\Program Files\Cura 2.1\resources\profiles\general
* C:\Program Files\Cura 2.1\resources\profiles\materials

####Cura 2.1.2 & 2.1.3 bug: https://goo.gl/R6YLx4  
Every files you will create has need a check, open it and delete every "M109", accept the first on top.  


##Cura 15.x.x
Load the profiles with: File > Open Profile  

--------------------------------------------------------------  
*Dave Calaway*.
