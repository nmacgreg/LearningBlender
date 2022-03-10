# Set Up Blenter Into Millimeters

## Updated for v2.9 / 3.0

* [Saving a default startup file](https://youtu.be/VihRvil3138?list=PL6Fiih6ItYsXzUbBNz7-IvV7UJYHZzCdF&t=120) with mm's set up

## The Older Course

* [How To - Set Up Blender into millimeters (mm)](https://www.youtube.com/watch?v=ZI49VIcISaw&list=PL6Fiih6ItYsX3qdwhEyd77zy82bM-I8t1)
    * By default, Blender is set in meters, which is probably appropriate for real-world monitoring, eg animation
    * RHS panel, LHS tiny tabs, find "Scene Properties", on the Units twistee, 
	* set Unit System to Metric 
	* set Unit Scale to 0.001 
	* set Length to millimeters
    * Now, your grid has disappeared.  Inside the main drawing canvas, top-right (by the axis control) find a twistee marked "Overlays" & click to get the "Viewport Overlays" menu. 
	* set Scale to 0.001 (grid reappears)
    * Next, you'll find if you scroll out, clipping pretty quickly makes your model disappear. On the Sidebar menu, RHS, between the canvas and the RHS menu, find "View" & click to open the View menu
	* Add a zero to the "End" field (10,000 mm)
    * (If you care about renders, select the Camera from RHS top panel; find the "Object Data Properties" (green) tiny-tab below, "Lens" find Clip Start...
	* Change "End", again adding a zero (1,000 mm), otherwise the camera will clip out too quickly, too!
    * His preferred AddOns:  Main menu, Edit -> Preferences -> Add-ons:
	* Object Bool Tool (for cuttng)
	* Mesh: LoopTools
	* 3D Print Tool Box
	* PDT (Precision Drawing Tools) 
        * Add Mesh: Extra Objects
	* (Gotta go into edit mode, back out, select something, to make new entries in the horizontal menu, RHS, for each of those add-ons)
    * Finally Edit -> Preferences --> *Hamburger Menu* ---> Save Preferences
