# Cultivation furniture v0.0.1

![image: the final prototype](wideShotFINAL.JPEG)

This repo documents my first attempt at designing and building a prototype for modular furniture in which you can store water (required for life) and grow things (plants, mushrooms, microorganisms, materials) in an urban home. It fits into a broader project together with the Flowing Futures collective (see repo [add link here]() ).

## the idea

Our agriculturtal and industrial production systems play an important role in the continued destruction of and extraction from our environments. Our dependence on it also plays a role in our reliance on work to secure our subsitence. This is especially stark in urban environments, and (among those who have a permanent home) especially for people who live in apartments. 

Cultivation furniture is a practical exploration (about how can we grow some of the things we need and want in our own homes) as well as way to invite people to reimagine the function and experience of domestic spaces. 

To begin making this idea a reality, I tried to find a minimum viable furniture.


## the process (what i did)

I landed on a small coffee table or bedside table as an initial furniture. The idea was to make it as modular as possible. That is why I opted for a triangle as a top / bottom shape (due to the ease of making various shape out of many triangles). The size of the triangle was chosen based on the size of wine bottles when arranged in either a very compact setup (which is not the one I opted for for the first iteration), or a more airy, simple setu, where wine bottles are only present in the center of the triangle and on the connecting sides. 

The cultivation I opted for in this first iteration is wick hydroponics. This is commonly described as the most simple hydroponics setup. It involves a substrate at the top (in this case, in the upper wine bottle, the base of which was cut off), and a nutriment solution at the bottom (the lower wine bottle, int this case). The two containers are connected via a wick (e.g an old textiele, or some string). The nutriment solution travels up to the plant's roots in the substrate via capillary action (for an explanation, see, for example: https://www.trees.com/gardening-and-landscaping/hydroponic-wick-systems).inital 

After initial drawings and musings I visualised my initial ideas in 3D by building an extremely rough prototype:
![image: rough prototype](roughPrototype.JPEG)

Much still had to be determined, e.g. the way the two trianglee boards should be connected.

After much thinking about how bottles could be arranged (and thus, how large the triangles should be)....

![image: prototyping glass arrangement](prototypingGlass.JPEG)

... I opted for a model where a central bottle could be surrounded by three more, and then connected to other triangles by another three. After prototyping in thin wood with a lasercutter and seeing what it looked like on 0.25L bottles, I cut it in plywood using Fablab Barcelona's CNC because that's what was available where I was. You could use any number of other materials, variations on shape and size. 

![image: cnc cutting](cncCutting.gif)

Somewhere in-between thinking about the triangles, I was also exploring various ways of connecting the wine bottles. 

![image: connected with copper](connectedWCopper.JPEG)
h
For example, I got enthralled with the aesthetic qualities of copper and latex tubing, so tried to build a contraption out of 18mmm copper connecctors and latex tubes. Unfortunately, this didn't work because the copper connectors didn't fit into the bottle.

While it didn't work out in the end, it did allow me to see if the modular setup made sense (I tought it did). Some tape was also requiree (as always..).

![image: modular setup](modularPretty.JPEG)

Since the copper version didn't work, I set out to find a different solution. I had a 3D printer at home, so I went for a solution involving that. 

To better understand what would work as well as the size of my wine bottle including differences in the flexibility of my PLA filament and to test my (new) 3D printer etc, I decided to print out an oil dispenser add-on for wine bottles (that I found on thingiverse: https://www.thingiverse.com/thing:4727790). 

![image: oil dispenser](oilWine.JPEG)

in this image you can also see an idea that emerged in that moment, which is to use ordinary elastic bands to create a seal.

With the rough method of production (3D printing with rubber bands) confirmed, I set out to create or find a model to connect the two bottles. Instead of drawing one myself, I decided to just scale two models I found on thingiverse to the size I needed: first a [simple connection](https://www.thingiverse.com/thing:5989941), and then a [T connector](https://www.thingiverse.com/thing:2204659) which allows us to add a water tube. These are originally designed for pneumatic tubes and hoses, respectively. Printed at 100% infill and with supports, they work fine with wine bottles.

![image: the simple connector, with supports still on](First3dPWithsupports.JPEG)

For the T connecctor, I believe due to me (or/and the default of Cura) positioning it horizontally instead of vertically, it was a bit of a pain to remove the supports that got built on the inside. 

Two problems were now left to be solved. The first, since I wanted to make a hydroponic setup, whith a plant growing out of it, I needed to cut the bottle. So far, the process I used is not perfect. It involves pre-cutting with a glass cutter...

![image: glass cutting](glassCUTTA.JPEG)

... heating the cut.. (for example by dipping some string into acetone and setting it on fire. 

![image: heat the cut](burninAcetoneGlass.JPEG)

and then plunging it into ice-cold water (didn't take a picture of that). 


The second problem is how to connect the two wooden triangles. After rejecting initial ideas of connecting them with rigid materials as well as of connecting everything to a central 3D printed part (creating a fragile single point of failure), I opted for connecting them with string using the following knot:

![image: tautline hitch](knot.PNG)
source: https://www.netknots.com/rope_knots/tautline-hitch

This allows us to increase tension continuously until we have the required balance between the three strings and the required tension overall. 

Bringing all elements together, this is the result:

![image: the final prototype](FINAL.JPEG)


## replication (how to build it)

To replicate this prototype, you can refer to the steps described above, but focusing on the useful ones. The files you need for that are all available in this repo (see the steps below).



### bill of materials (what you will need)

#### machines (can partly be replaced by manual labour)
* CNC (can be replaced by manual labour, might be a bit tedious. Alternatively a sanwich of laser cut plywoood could also work)
* 3D printer (harder to replace, needed to cut these connector pieces: [simple connection](https://www.thingiverse.com/thing:5989941), [T connector](https://www.thingiverse.com/thing:2204659) scaled to the size of your wine bottle)

#### tools
* knife / box cutter
* glass cutter
* computer with a slicing software (like Ultimaker Cura)
* a way to cool (like a fridge or a balcony in cold weather)

#### other materials
* plywood or any other relatively thick material
* old wine bottles
* string (natural fiber)
* latex tubing (of the right size for your scaled connector pieces)
* acetone

for the (unfinished) hydroponics part:
* a wick (old textile, or use the string)
* nutriment solution
* substrate (e.g. expanded clay)
* hand water pump 


#### optional but will make things easier
* tape

### recipe (step by step, how to make it)

#### the triangles at the top and bottom
1) Prepare the file for the CNC, potentially based on this file from this very repository: [BIGtriangleThoing.3dm](/BIGtriangleThoing.3dm). The holes for string must be added to the file or done by hand (as I did)
2) cut the tiangle and circles seen in the file, either by hand or with a CNC, either in plywood or some other hard and sufficiently thick material
3) sand them

#### the connector pieces
1) download one or both of the models: [simple connection](https://www.thingiverse.com/thing:5989941), [T connector](https://www.thingiverse.com/thing:2204659) if they make sense for you. Otherwise find or make another connector model
2) slice it (e.g. using Cura)
3) print it (or get it printed)
4) remove the supports
5) optional: sand / make smoother

#### the bottles
1) find at least two old bottles 
3) cut one of them in the following way
   a) pre-cut the bottle at the desired height with the glass cutter 
   b) prepare an ice bath (water with ice) 
   c) prepare put the string in acetone
   d) tie it around the bottle and set it on fire
   e) quickly put the bottle in the cold water
   f) gently nudge/break the bottle along the line
   g) if it doesn't work, repeat the steps or find an alternative solution. This one is not perfect..
   
   
####  connect the parts
1) put one of the triangles on the floor
2) put the first wine bottle in it (potentially adding tape or further sand the holes to adjust the snugness)
3) put one of the connector pieces into the bottle
4) put the other bottle on top (with the top looking down)
5) put the other triangle on top
6) connect the two triangles with a tautline hitch (see in the section 'what I did') 
7) tighten those hitches as needed to achieve a nice and springy feeling. The furniture should be stable in a way akin to a young tree

#### set up the hydroponics setup
This part, I did not quite finish exploring. However, you should be able to install a wick (e.g. an old textile), and add (or keep at hand) the water pump (with a tube that fits all the way through) to periodically remove the nutriment solution. When adding the nutriment solution, you can just pour it from the top. Improvemetns and (hi-lo tech) automation could be added here. Something to explore further. 


