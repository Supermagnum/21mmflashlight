# 21mmflashlight
This is a repository for a flashlight, takes two 21700 batteries
It can be made using a normal lathe and a drill press or a milling machine. A multi axis CNC is required for the fancy engraving.

You will need a round stock that has 60mm diameter and suitable length, material 6061 aluminium alloy to make this flashlight. You will need to thread the parts as you see fit, and add knurling.

If Anodizing is added as a surface treatment, the threads must be left bare, as the chassis is DC negative and electric connections must be preserved.

It takes two 21700 lithium ion batteries Batteries ( 21 mm diameter and 70mm length), I think that protected ones with a button top should fit. 

It is also smart to use a good quality thermal paste on the backside of the LED pcb. Something like NT-H1 from Noctua is good. Ordinary electric conductive copper paste can perhaps be used on the threads on the part that holds the two PCB's to improve the thermal conductivity.

LED driver:
http://www.international.mtnelectronics.com/index.php?route=product/product&path=67_117&product_id=888
Note on the LED driver: I dont know if it has any protection agains reverse polarity, but its easy to add that. Just use this PCB:
https://oshpark.com/shared_projects/QlLKpYoS

LED ( You will need the 6V 20mm version ):
http://www.international.mtnelectronics.com/index.php?route=product/product&path=60_114&product_id=867

OFF/ON switch:
https://www.digikey.com/product-detail/en/te-connectivity-alcoswitch-switches/AV1911000Q04/450-2229-ND/6043720
The part number is: AV1911000Q04 
One leg of the switch must be connected to the endcap. The switch may require a small spring and a plastic spacer so the other leg is in contact with the batterys negative therminal. It's also some soldering involved, the legs on the switch,and the wires from the driver PCB is the ones that needs soldering. That is four points total.



All the IGES files,STL files and SVG blueprints are in their folders.
The vinking-holder file has a engraving with graphics from a sword hilt found at Alm in Stange, Norway. It's from around year 800.

