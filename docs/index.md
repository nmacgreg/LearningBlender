# Learning Blender

* [How To - Set Up Blender into millimeters (mm)](https://www.youtube.com/watch?v=ZI49VIcISaw&list=PL6Fiih6ItYsX3qdwhEyd77zy82bM-I8t1)
    * By default, Blender is set in meters, which is probably appropriate for real-world monitoring, eg animation
    * RHS panel, LHS tiny tabs, find "Scene Properties", on the Units twistee, 
	* set Unit System to Metric 
	* set Unit Scale to 0.001 
	* set Length to millimeters
    * Now, your grid has disappeared.  Inside the main drawing canvas, top-right (by the axis control) find a twistee marked "Overlays" & click to get the "Viewport Overlays" menu. 
	* set Scale to 0.001 (grid reappears)
    * Next, you'll find if you scroll out, clipping pretty quickly makes your model disappear. On the horizontal menu, RHS, between the canvas and the RHS menu, find "View" & click to open the View menu
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
	
* [The Basics of Blender 2.82 Precision Modeling with PDT - How To ( Tutorial Part -1 )](https://www.youtube.com/watch?v=8a4mm-zb3nk&list=PL6Fiih6ItYsX3qdwhEyd77zy82bM-I8t1&index=2)
    * He warns that Numpad + 3-button mouse are critical
    * From Edit -> Preferences --> Interface, set "Resolution", if you have a 4k monitor or poor eyesight
    * "Viewport" - official name for the main modeling canvas
    * Basic controls: 
	* Click & hold scroll-wheel (middle-button) + move == rotate viewport
	* Shift + click-middle + move == panning viewport
	* Control + click-middle + move == zoom/retract viewport
	* Completely lost in the Viewport? 
	    * Click RHS upper menu: Select anything (cube) & hit "." on the Numpad == fills the frame with the selected object
	    * (Can also get that from the Viewport's View --> Frame Selected menu)4
    * For this video, we'll mostly work in the "orthographic" viewpoint -- Numpad 7, or click the Z in the axis-bubble (eg from the top)
    * The Viewport has several different modes
	* Object is the primary mode; select one object & find the horizontal menu "Item", to bring up the Transform menu... *where you can find xyz dimensions for the cube!*  At last!
	* TAB toggles back-and-forth between Object and Edit modes!
    * In Edit Mode, 
	* right beside the mode-selector box, there are 3 tiny what-did-you-want-to-select boxes: Vertext, Edge, and Face
	* ... allowing you to select and delete or add stuff -- I can delete the top of the cube!
    *  The CURSOR is the center of the ViewPort -- get to know this guy
    * Example: 
	* In Edit mode, select everything, delete it. 
	* Hit Numpad 7 to go Orthographic
	* Shift-A & add a single vert
	* "e" to extrude the vertex
	* "x" to constrain it in the X axis
	* "10" to give it a dimension (Notice, top-left of the Viewport, it says: "D [10] = 1cm (10mm) along global X"
	* Enter or Click to confirm
	* [@timecode](https://www.youtube.com/watch?v=8a4mm-zb3nk&list=PL6Fiih6ItYsX3qdwhEyd77zy82bM-I8t1&index=2) you can adjust the size & colour of vertices & edges, if you're having trouble seeing them
	* Make 3 verts of a square
	* Use PDT Design tools -->  Join 2 verts
	* Select all 4 verts
	* Hit "F" to fill it ! NEATO! 
	* Finding the middle: 
	   * Deletes an edge
	   * Selects the 2 points missing an edge
	   * In PDT Design Operations, 
	   * 

