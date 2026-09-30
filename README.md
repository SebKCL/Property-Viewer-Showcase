# London Airbnb Property Viewer (Java GUI)

> A desktop application that loads London Airbnb listings from CSV and lets users browse them, save favourites, view locations on a map and see viewing statistics.

🔒 **The source code is in a private repository** because this was university coursework at King's College London. I'm happy to walk through the code on request.

## Features
- Loads and parses a real-world Airbnb dataset from CSV
- Browses properties one at a time, with next/previous navigation that wraps around at either end
- Toggles favourites, with the favourite status shown in the status bar
- Opens the current listing's location on a map (I fixed an existing bug where it used the wrong listing)
- A statistics window showing the number of properties viewed and the average price of those viewed

## Design
The code keeps data (`Property`, `Portfolio`), application logic (`PropertyViewer`) and the GUI (`PropertyViewerGUI`) in separate classes, with a focus on correctness, readability and documentation.

## Skills demonstrated
Java · GUI event handling · file I/O and CSV parsing · object-oriented design

## Tech stack
Java · BlueJ
