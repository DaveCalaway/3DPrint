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
  * PLA: 30 – 70 mm/sec  
  * ABS: 35 mm/sec  , you can rise up to 45mm/sec after 5 layers.
2. --------

### Retraction settings - ONLY for Optimus e3d_v6 - :
 - Retraction distance: 0.5 mm
 - Retraction speed: 20 mm/s


### Temperature guide line:  
* **ABS**:
	* *Printer*: 245°
	* *Bed*: 110° is perfect.  
* **HIPS**:
	* *Printer*: 240°
	* *Bed* : 110°
* **PLA**:   
	* *Printer*: 195°
	*  *Bed*: 40° with hair spray remain the best solution ( default setting ). If you have not hair spray, you must set 60° on the bed.  

### Fan guide line:
For **PLA** prefer set the speed layers by layers on machine, Cura does not work good at free wheel....  

**ABS** 80 of 255 - or 30% - only after the first layer.  

**HIPS** no fan needed.

Remember Gcode's setting, useful for Cura 15.x.x:  
* fan on: M106 S[0-255]
* fan off: M107  

## Cura 2.x.x / 3.x
Used the image to setting machine and profiles.


## Cura 15.x.x
Load the profiles with: File > Open Profile   

--------------------------------------------------------------  
*Dave Calaway*.
