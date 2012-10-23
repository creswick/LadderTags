LadderTags
==========

Printable 3D Model(s) for a hanging competition ladder.


== Printing with ReplicatorG ==

 * Load the stl for the model.
 * Generate GCode.  I've been using the following settings for our Replicator with two extruders:
   * Left Extruder (white)
   * Do not use raft.
   * Support material: None
   * Use default start/end gcode
   * Use Print-O-Matic
   * Object infill (%): 10
   * Layer height: 0.27
   * Number of shells: 2
   * Feedrate: 25
   * Travel Feedrate: 40
   * Print temperature: 235
   * Filament Diameter: 1.8
   * Nozzel Diameter: .4
 * Click 'generate gcode'
 * Open the GCode tab, and change the platform temp to 120:
   * Find the line: `M109 S110 T1 (set HBP temperature)` and change it to: `M109 S120 T1 (set HBP temperature)`
 * Export to s3g and print.
