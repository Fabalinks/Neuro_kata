# Neuro_kata
Neuroscience kata
Intro:
 You are a Neurosurgeon in the middle of surgery;  you are doing a very precise targeting for a virus injection and then electrode implant. Your robotic arm broke and all you are left with is a command line with no interface. You need to write a quick yet very efficient function to position your implant and inject the virus. Everything is in surgical coordinates – AP DV ML, you are at a starting position at Bregma AP = 0 ML=0 DV = 0 and you need to get to “insert favorite brain region” in whatever species you work with. For example you can use the Rat Hippocampus  – AP = -4mm ML=2mm DV =3.2mm 
 
So create a function “Your_favorite_brain_region”: 

That moves the stereotax from Bregma to your spot or region, but it needs to go ML then AP and then finally DV, else you destroy a lot of tissue. Showing location after every move in one axis. 

If you can code it in one hour and it can be executed just by one command your team saved the patient. Otherwise you have major complications. 
Here is a simple Rat brain atlas for reference  - http://labs.gaidi.ca/rat-brain-atlas/ 
Other species can be found here https://scalablebrainatlas.incf.org/  - find species and your region and use RAS ( right,anterior,superior) coordinates by hovering over your favorite region to position the surgical stereotax

More info about neurological coordinates 
http://www.grahamwideman.com/gw/brain/orientation/orientterms.htm
