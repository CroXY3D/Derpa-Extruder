# Derpa Mini
 
A lightweight extruder using a 70g LDO Nema14 motor with integrated 10T pinion.  Printed parts total 4g.  Total weight of Derpa + BMG is 140g.

The 10 tooth pinion on the LDO motor along with the BMG gear gives a 5.1:1 gear ratio, which is enough to push 14mm^3/s through an e3dv6 with 0.4mm nozzle.  It should be able to push more through a Volcano.

 ![Image of Derpa Mini](https://github.com/wesc23/Derpa-Mini/blob/master/images/derpa-mini.png?raw=true)
 
 ![Image of Derpa Mini](https://github.com/wesc23/Derpa-Mini/blob/master/images/derpa-mini-rear.png?raw=true) 
 
 [Uses this 70g LDO Nema14 motor](https://www.printedsolid.com/products/ldo-nema-14-motor-ldo-36sth17-1004ahg?variant=32690500370517)

Note, you may have to file off a super tiny bit of the lower ear as it can interfere with the screw holding the BMG together.  

BOM:
Qty 1 BMG
Qty 1 LDO Nema 14 Motor
Qty 1 M3x35 SHCS
Qty 2 M3x45 SHCS
Qty 1 M3x6 SHCS
Qty 4 M3x? Screws to mount.

RRF 3 Settings:
'''M906 E300  ; 300 mA current (try 350)
M92 E703   ; steps/mm
M201 E100  ; Accel, Not tuned
M203 E1800 ; Max Speed
M566 E1000 ; 1000 RRF InstantDv
'''

