# Introduction 
This document will show all the process I went through building this controller. I don't think this shuld be called a tutorial, more just like a showcase of how could this be done. There are many ways you can do this, this is just one way to it.

# First batch of things to buy
## Buttons
### Taobao
I went for the only option that was reachable for me, taobao buttons, you can find them by searching `舞萌按键`. With this method you can also buy afficial spacers but they are easily 3D printable. To get higher quality ones, try asking people for "Rabbit Buttons" as they are higher qualuty than most of the ones that are on taobao

-Buttons from taobao photo-
### Bluespringexpress
Now there is also another method, wchich is buying them from [bluespringexpress.net](https://bluespringexpress.net)
### External sourcing, private sellers
There is some chance you can find some private sellers on rhythm game cabs discord so if its worth trying

## Wood
The core of where buttons, cables and glass are connected. I suggest going for plywood 80x80 cm, it can be bigger or smaller but remember that minimum is 70x70 or 60x60 if you only want to play on the touch (it is possible but not reccomended because in some cases you need to use button in the game). Second option could be HDF sheet, basically same thing but on plywood it's easier to screw in buttons and spacers. I went with one cm thick but it could be more if i would say

## Glass
I came up with an idea of hexagonal glass with the dimensions below. I can be honestly whatever you want, wheter it is square or hexagon. Remeber though about cables plus that diameter of circicle on arcade size controller is 52cm and you need some more space to mount it. I went with 4mm hardened glass, but if you can find minimum would be 3mm if it's more conventional. Provide glass making service with your dimensions or cut it out from paper(EXTREMLY RECCOMENDED, WILL EXPLAIN LATER) and give it to them on place if possible. 

## ITO film
I ordered mine from taobao with proxy service to Europe, but found similar option on aliexpress so go with whatever suits you better. Here is link to one i bought from tabao -link-. Main thing you are looking for is 1 square meter, with applied glue on one side. About resistance, I have no clue that it changes but i went with 150ohm. 

## TV and mount
Highlt reccomend to buy it early to get measurements for later. 43 inch is DX size which this project is all about so accquire one. No need to go for 120hz as it is cashgrab and the game sucks on 120hz anyway, so dont overpay. If you want to save it later for ADX from yuancon try to find one that is less than 6.4cm thick or on this list https://docs.google.com/spreadsheets/d/1WN50pyJEPpXR32UTsEzsKe4Qm-EUAQgwmkCBX3kWB1Q/edit?gid=0#gid=0. About the mount, try to find anything as flat as possible without any additional motion addons. Espacially good one would be one with a lot of holes as it will be used to scre wit to aluminum profiles.

## Electronics and Rest

### PCBs
Buttons: I ordered one form tabao but recentyl seen on aliexpress as well here are links

Touch: Mai_pico by whowechina is easiest to go for right now go and build it but remember not to solder mpr121 to pcb but 90 degree connector as shown here. You can also use this pcb for buttons but i just had another one earlier so I just used the already premade one

### Cables, wires, and connectors

-8 of 3 pin female to female connector for buttons.
-3 of 6 pin female to female connector for mpr. Reccomended 50cm or less due to i2c communication limits.
-Bunch of other female to whatever cables, 100cm for connecting ito touch zones to mpr
-Copper wire 0.07mm or 0.1mm, just anything in the similar size
-90 Degree male pin connector 2.54mm

### Screws and glass holders
Anything that will hold your buttons and spacers without going through the wood and potentially damaging glass or cables
To hold your glass use anything silimar to this

# First assembly
## Cut circle in wood
Go to your nearest place where it can be done and ask for circle in the exact center of your wood that is 52cm diameter.
## Engrave space for glass (Optional)
This is optional stuff to make sure that your glass is not moving. Find the nearest service where it can be done and engrave the exact same size from the center for 1mm less than your glass thickness. 
## Screw in spacers and buttons
I reccomend starting from spacers as it is easier to get them in correct place with simple measuerments, so place them in the right place and outline with for example pencil. Then install buttons between those outlines. Remember there should be minimal space between buttons and spacer so it isnt like 100% fit into. Or maybe i had but cutting service of circle, whatever. After this step remember to drill out holes for buttons cables go to back of the board and check if there are any screws that went through to the other side and sand them of or however you like to do it

## Cut ITO
There are many designs for ITO as you can see here but i went with this one
