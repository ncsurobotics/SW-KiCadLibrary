# SeaWolf KiCad Libraries

## Installing Libraries in KiCad

1. Clone this repository somewhere on your system. The location does not matter.
2. Open KiCad. Close any open project (File > Close Project)
3. Preferences > Manage Symbol Libraries
4. On the Global Libraries tab select the folder icon at the bottom (Add existing library to table)
5. Navigate to wherever you cloned this repo. Choose the `SWLib.kicad_sym` file.
6. Click OK to close the symbol library table.
7. Preferences > Manage Footprint Libraries
8. On the Global Libraries tab select the folder icon at the bottom (Add existing library to table)
9. Navigate to wherever you cloned this repo. Choose the `SWLib.pretty` folder.


## Updating Libraries

To update the libraries, simply run `git pull origin main` where you cloned this repo. Then restart KiCad.


## Library Structure

- `SWLib.kicad_sym` file: This is a KiCad symbol library. It should only be edited using KiCad's symbol editor.
- `SWLib.pretty` folder: This is a KiCad footprint library. It should only be edited using KiCad's footprint editor.
- `SWLib.3d` folder: This is a folder where 3D models to be used on footprints should be placed. This folder contains stl and step files.


## Adding a Part to a Library

TODO
