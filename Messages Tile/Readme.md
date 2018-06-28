Messages Tile
==============================
This simple tile demonstrates the following:

1) Fetching the token (or logging in)
2) Making a $.ajax request to the graph with the token
3) Using jQuery to manipulate the tile's contents
4) A list including the users Email's and Teams messages

Keep in mind that the tile does NOT provide rigorous error-handling, so please improve the solution for production code.

Loading the Tile
----------------------------------
The provided JSON file is an exported page. To load it:

1) Open the LiveTiles Design Home page (/LiveTilesDesign/Home.aspx from your site collection)
2) Click "Create"
3) Click "Import Page"
4) Click "Choose File"
5) In the open file dialog, select the "Messages Tile.json" file
5) Confirm with "OK"

A responsive page with a single row, column, and tile should load - showing the current O365 user's information.