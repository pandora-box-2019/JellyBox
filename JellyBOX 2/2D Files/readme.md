## File Formats

The master for geometry is an Illustrator file (.ai), but the master for production are Rdworks (.rld) files. The .ai files do _not_ contain all the informations, but only the shapes and colors. Line processing like dotted line, dashed line... is done in RDworks and is contained in the .rld files. 

If you can, we recommend you use RDworks with your laser. 

If you can't, then still try and download RDworks, and use the Preview function to see what all the settings do so you can replicate it in your laser host.

## Laser Control: Rdworks

You can find it here: http://www.rd-acs.com/down.aspx

RDcam/ RDworks is a Chinese piece of software that drives Ruida style lasercutting controllers. 

These are very common; known in the US as the ubiquitous 'Chinese lasercutters'.
Rdworks is a surprisingly capable piece of software. We use it to control our lasercutters. You can open the rdworks files, adjust the cutting settings to fit your laser (power/size) and get on cutting. 

Note that we run two passes on a regular high power CO2 laser. One is engraving - this one is run de-focused on purpose to get a wider and smoother engraving line. The second run is the cut - the black line. 

Get plastic covered acrylic if you can. Paper covered acrylic is more common, but the paper is a major pain to remove after the parts are cut. 
Leave the bottom protective sheet in place to mitigate burnup, but remove the top sheet to get a more predictable engraving. You may need to run active side fan while engraving to get less particle deposition. Also, air assist should be off for engraving (but definitely on for cutting!)

If you have access to an engraving machine, then feel free to use that, especially if you're only cutting one set or so!

PS: You can export geometry out of rdworks (ai, dxf) if you want to use other lasercutting controller. Just make sure to preview how all the dashed and dotted lines are rendered! This is done in rdworks, not in the geometry itself. 