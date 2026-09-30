# London Airbnb Property Viewer (Java GUI)

> A desktop app that loads London Airbnb listings from a CSV file. You can browse them, save favourites, open each on a map and see your viewing stats.

🔒 The code sits in a private repository because this was King's College London coursework. Ask me and I'll walk you through it.

## Features
- Reads a real Airbnb dataset from CSV
- Shows one listing at a time, with next and previous buttons that wrap round at each end
- Lets you mark favourites and shows the status in the status bar
- Opens the listing on a map. I fixed a bug that sent it to the wrong listing
- A stats window with the number of listings you've viewed and their average price

## Design
I split the code into data (`Property`, `Portfolio`), logic (`PropertyViewer`) and interface (`PropertyViewerGUI`), and documented each method.

## Skills
Java · GUI event handling · file I/O and CSV parsing · object-oriented design

## Tech stack
Java · BlueJ
