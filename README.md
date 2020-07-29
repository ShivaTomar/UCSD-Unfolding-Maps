# UCSD-Unfolding-Maps
An Interactive real-world earthquake &amp; airport data visualization using Java, Unfolding maps library &amp; Processing GUI for the graphical interface. Earthquakes are happening daily around the world. Geological analysis suggests which location will be prone to higher seismic.

- Earthquake data from https://earthquake.usgs.gov/earthquakes/
- Processing - https://processing.org


## Module 6 contains the final output of the program.

Capabilities includes:

1. Keyboard shortcuts

* Change map providers
- Show only the recent earthquakes or show it all

2. Mouse Hover

- Show a marker's detail drawn on top of other graphics
- Dynamic latitude and longitude on the lower right side of the map

3. Mouse Clicks:

- When clicking a city marker:
    + Shows the airports within 50km
    + Shows an earthquake if the city is affected by its threat circle
    + Hides other city marker
    + A popup menu appears on the left side of the map to show the count of nearby earthquakes, average magnitude, and the most recent earthquake occurred
    
- When clicking an earthquake marker:
   + Shows a city marker if it is within its threat circle
   + Shows airports affected by its threat circle
   + Hides other earthquake marker
   
- When clicking an airport marker 
   + Draw a line to its routes and hides other airports
   
   
# INSTALLATION

Import this folder in Eclipse ('File' -> 'Import' -> 'Existing Projects into Workspace', Select this folder, 'Finish')

# MANUAL INSTALLATION

If the import does not work follow the steps below.

- Create new Java project
- Copy+Paste all files into project
- Add all lib/*.jars to build path
- Set native library location for jogl.jar. Choose appropriate folder for your OS.
- Add data/ as src

# TROUBLE SHOOTING

Switch Java Compiler to 1.6 if you get VM problems. (Processing should work with Java 1.6, and 1.7)

