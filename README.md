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
  * PLA: 20 – 70 mm/sec  
  * ABS: 35 mm/sec  , you can rise up to 50mm/sec after 10 layers.
2. --------

### Retraction settings:
 - Retraction distance: 5 mm
 - Retraction speed: 30 mm/s


### Bed guide line:  
* **ABS**: no problem with default setting.  
* **PLA**: 40° with hair spray remain the best solution ( default setting ). If you have not hair spray, you must set 60° on the bed.  

### Fan guide line:
For **PLA** prefer set the speed layers by layers on machine, Cura does not work good at free wheel....  

Remember Gcode's setting, useful for Cura 15.x.x:  
* fan on: M106 S[0-255]
* fan off: M107  

**ABS** don't need fan, only in rare cases.  

##Cura 2.3.x
Used the image to setting machine.  


##Cura 15.x.x
Load the profiles with: File > Open Profile  

--------------------------------------------------------------  
*Dave Calaway*.
