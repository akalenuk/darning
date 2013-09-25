darning
=======

GIMP script for cleaning pictures. It takes a background from a selection border (it should be rectangular by the way) and interpolates the selection contents based on this border.

<img src="screenshots/E_before.png"> → <img src="screenshots/E_after.png"> 

Works ok with corners and borders. Yet it is slow and doesn't support undo, so use at your own risk. 

This script was built based on one of the features of my other project - the Unpager - https://github.com/akalenuk/ Unpager can do darning not only for rectangular forms, but for any quadrilateral. The complete simplicial darning feature (for working with basically any selection) is currently in development.
