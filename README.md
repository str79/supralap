# supralap
none

There is a map to the left of the group, the map can be moved 

when you click on a group name, the list of this group is expanded 
clicking on a peephole on a list item shows / hides it on the map, and also activates / deactivates the peephole itself 
a click on the eye on the name of the group activates / deactivates the eye itself, sub-elements, and also shows / hides them on the map 
double click on an element - center it on the map 
double-clicking on any place on the map displays its coordinates in the console and copies them to the clipboard (service) 

New story group: 
Those elements are added to it that were deactivated by the eye on the element (not on the group). 
New elements have the same functions as ordinary ones, but in addition to activating / deactivating an element, it not only switches the markers on the map and its eye, 
but it also finds the same eye in other groups (with the same description, number, coordinates) and also switches it. 
You can also delete history items. 

When you hover over the name of an element, it becomes foreground on the map. 
When you hover over a marker on the map, it becomes foreground. 

There is also a button to include everything - it includes all the elements that the marker also sees. 

By double-clicking on the inscription "group" an array of history is copied so that you can replace it with the existing one 
because in the history only serial numbers (id) of markers on the map are stored; information is taken from markers on the map, group numbers are taken from lists that correspond to id on the map. 
If you press alt when clicking, the current group elements are copied to the clipboard, but only active, to replace the current array (to track progress), 
in particular, it also takes the id of markers as the basis for collecting information, because there are no numbers and other things 

Markers on the map can also be moved as well as the map, and with the shift key held down, you can edit the description that will be displayed when copying the story. 
Markers on the map can be turned off by double-clicking on them, while the trigger fires as if it would turn off the peephole individually. 
Markers on the map can be moved with alt pressed - then a copy of the label is created. 

History is stored in cookies, also just in case stored in localStorage 
When you click ctrl on the map, a circle appears, turns off in the same way, the circle can be moved and enlarged with the [] buttons, the point is that when you hover over a specific group of markers, 
a list of what’s in the circle with the number and description appeared. 

The order of work is approximately the following: we press the button to turn on everything, as we progress through the game we turn off the collected points individually, and our path is remembered in history.

If you click on the title of the story with alt pressed, the story is cleared.

engine version 1.0
