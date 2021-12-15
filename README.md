# Gamesense API Extension Library

## Modifications
* **Client** - Trace line returns end position, all positions and sizes return vectors, and you can get the dpi scale now.
* **Entity** - Entities are now OOP, and all positions return vectors.
* **Renderer** - All renderings take vectors and color objects now, all size returns are now vectors as well.
* **Printing** - Printing with commas will now seperate the datatypes instead of printing them in a line like before, also datatypes are converted.

## Added Libraries
* **Vector** - Custom vector library that is seperate from the require vector class to use for the modified libraries.
* **Color** - Custom color library to make colors easily and clean up code for renderings.

## Function Modifications / Additions
* **client.get_dpi** - Added so you can now get the menu DPI scale easily.
* **client.trace_line** - Traces now return the ending vector along with the percentage and entity hit within a table.
* **renderer.rectangle** - Adds a radius argument for rounding a rectangle.
* **renderer.rectangle_outline** - Adds a outlined rectangle with the same arguments as the regular rectangle.
* **renderer.world_to_screen** - Returns nil if it failed to calculate the position instead of returning (0, 0).
* **renderer.circle_3d** - Adds a circle that can be rendered in 3d space.
