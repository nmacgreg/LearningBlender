# Precision Modeling in Blender, with PDT

## Updated for v2.9 / 3.0

* [This video got updated](https://www.youtube.com/watch?v=qzhgrHDDR7I&list=PL6Fiih6ItYsXzUbBNz7-IvV7UJYHZzCdF&index=2), before I started taking the course; I looked at the old one.  The individual videos don't map exactly to each other
* New: Edit --> System --> Preferences --> System: Set "Undo Steps" to max == 256 (although this can make your system slow; reduce it, if so!)
* New: No Numpad for views? Alt + Middle button + *gesture what you want to see!* & it'll Numpad-7 for you!
* The X/Y/Z navigation circle widget is called, "The Gizmo"
* [@12:17 he demonstrates both "walk" and "fly" navigation](https://youtu.be/qzhgrHDDR7I?list=PL6Fiih6ItYsXzUbBNz7-IvV7UJYHZzCdF&t=737)
* [Next new vid, "Precision Addons"](https://www.youtube.com/watch?v=qzhgrHDDR7I&list=PL6Fiih6ItYsXzUbBNz7-IvV7UJYHZzCdF&index=2)
	* Notes that some Addons are from Blender; others are community-supported; many ship with Blender, but you can find externals, too!
	* Notes that you can see authorship + URL for plugins, from the twistee beside each
    * That horizontal menu, RHS of the Viewport, is called the Sidebar... you can open it with "N"
	* [@3:29 he lists them all](https://youtu.be/v9tbXF410SU?list=PL6Fiih6ItYsXzUbBNz7-IvV7UJYHZzCdF&t=209)
	* 3D View: MeasureIt
	* 3D View: Stored Views
	* Add Mesh: Extra Objects
	* Add Mesh: BoltFactory
	* Export Autocad DXF
	* Import Autocad DXF
	* Mesh: Tincad Mesh Tools
	* Object: Bool Tool
	* Object: Align Tool
	* Mesh: 3D Print Toolbox
	* Interface: Modifier Tools
	* Mesh: F2
* Mentions [BlenderArtists.com](https://blenderartists.com) as a forum, and a place where you'll find *external* community-developed plugins

##  v2.82

* Note: PDT = Precision Drawing Tools, a plugin
* [The Basics of Blender 2.82 Precision Modeling with PDT - How To (Tutorial Part -1 )](https://www.youtube.com/watch?v=8a4mm-zb3nk&list=PL6Fiih6ItYsX3qdwhEyd77zy82bM-I8t1&index=2)
* He warns that Numpad + 3-button mouse are critical
* From Edit -> Preferences --> Interface, set "Resolution", if you have a 4k monitor or poor eyesight
* "Viewport" - official name for the main modeling canvas
* Basic controls: 
	* Click & hold scroll-wheel (middle-button) + move == rotate viewport
	* Shift + click-middle + move == panning viewport
	* Control + click-middle + move == zoom/retract viewport
* Completely lost in the Viewport? 
	* Click RHS upper menu: Select anything (cube) & hit "." on the Numpad == fills the frame with the selected object
	* Or, get that from the Viewport's View --> Frame Selected menu
	* Or, Shift-C
* For this video, we'll mostly work in the "orthographic" viewpoint -- Numpad 7, or click the Z in the axis-bubble (eg from the top)
* The Viewport has several different modes
* Object is the primary mode; select one object & find the Sidebar menu "Item", to bring up the Transform menu... *where you can find xyz dimensions for the cube!*  At last!
* TAB toggles back-and-forth between Object and Edit modes!
* In Edit Mode, 
* right beside the mode-selector box, there are 3 tiny what-did-you-want-to-select boxes: Vertext, Edge, and Face
* ... allowing you to select and delete or add stuff -- I can delete the top of the cube!
*  The CURSOR is the center of the ViewPort -- get to know this "life-preserver"
* Example: 
* In Edit mode, select everything, delete it. 
* Hint: in Edit mode, hot keys 1,2,3 select vertex/edge/face operating modes
* Hit Numpad 7 to go Orthographic
* Shift-A & add a single vert
* "e" to extrude the vertex
* "x" to constrain it in the X axis
* "10" to give it a dimension (Notice, top-left of the Viewport, it says: "D [10] = 1cm (10mm) along global X"
* Enter or Click to confirm
* [@timecode](https://www.youtube.com/watch?v=8a4mm-zb3nk&list=PL6Fiih6ItYsX3qdwhEyd77zy82bM-I8t1&index=2) you can adjust the size & colour of vertices & edges, if you're having trouble seeing them
* [@10:45 he explains snapping](https://youtu.be/8a4mm-zb3nk?t=654)
	* Snapping menu is top-dead-center in the Viewport
	* Check "Absolute Grid Snap" & choose "Increment" (as the thing-you-want-to-snap-to)
	* Now select a vertex; hit E-for-extrude... notice that it's *not* snapping
	* *Hold down Ctrl to get snapping-to-the-grid*
* Make 3 verts of a square
* [Use PDT Design tools -->  Join 2 verts](https://youtu.be/8a4mm-zb3nk?t=721)
* Select all 4 verts
* Hit "F" to *fill* it ! NEATO! 
* [Finding the exact middle of 2 verteces @12:59](https://youtu.be/8a4mm-zb3nk?t=779)
	* Deletes an edge from the existing square
	* Selects the 2 verteces now missing an edge
	* In PDT Design Operations, 
	   * Working Plane: Top(X-Y)
	   * (1) Select Operation: "Move Cursor"
	   * "Do (1) at % between selected points"...
			* Change the unmarked RHS field beside it to "50"
			* Make sure "[2] %" is selected -- click it, and the cursor will move
		* Now Shift-A to add... A single vertex *inserted at the cursor!*
* [Finding the intersection point of two edges @15:15][https://youtu.be/8a4mm-zb3nk?t=915]

## Assignment:  Floorplan of your house

* He suggests that you build a floorplan of your house using the techniques you just learned!

## My questions at this point

* Now that I can select faces, I can delete the top face off the incipid default box that appears every time you open Blender
* Knowing now that the box is *hollow*, can I set the thickness of a line or a face? 
	* Thinking back to the Stormtrooper mask planter I printed... 
		* what would that look like, imported?
		* Could I see the weak areas, where it leaked, when printed? 
		* Could I increase the thickness of the walls, slightly?

