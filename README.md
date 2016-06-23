# 3DPrint
Machine setting for 3D Printers  

This repository it's made for [**Optimus**](http://goo.gl/feKXvQ)'s printers.  

## Layers height:  
Formula:  
`nozzle / 2` max  
`nozzle / 4` min  

## Speed settings:  
1. **Plastink** 
  * PLA: 35 – 80 mm/sec  
  * ABS: 35 mm/sec  , you can rise up to 50mm/sec after 10 layers.
2. --------

## Bed guide line:  
* **ABS**: no problem with default setting.  
* **PLA**: 40° with hair spray remain the best solution ( default setting ). If you have not hair spray, you must set 70° on the bed.  

## Fan guide line:
For **PLA** prefer set the speed layers for layers, Cura does not work good at free wheel.... By default i set, only for PLA, speed 100 at the start.  

Remember Gcode's setting:  
* fan on: M106 S[0-255]
* fan off: M107  

**ABS** don't need fan, only in rare cases.  



*Dave Calaway*.