# TreeViewer
Fault Tree Viewer

Currently only reads RSA format. 
Make sure your RSA file is encoded in UTF-8. RiskSpectrum may export it in UTF-16. If so, it needs to be transcoded to UTF-8 before use. The code currently doesn't do it internally.

## Usage

Download TreeViewer.HTML.  No server is needed - it works directly in the browser with no extra tools required.
Load the RSA file (encoded in UTF-8) select the Fault Tree that you want to explore and scroll down to the resulting view. For better visibility download the HTML for the selected tree an open in a new browser window.

## Capabilities 

You can zoom in and out and pan with the mouse in a very intuitive way.
The node descriptions are hidden by default to keep the structure more visible. The description appears automatically when you hover the mouse pointer over a node. There is also a toggle to switch all descriptions on/off.

Clicking on a gate causes it to collapse into a transfer. Clicking on a transfer expands it. 

There is also a toggle to cascade the transfer collapse down to the children gates. This allows the user to expand the structure one transfer at a time.

## Limitations 

- The RSA needs to be encoded in UTF-8.
- The CCF Basic Events are not included in the tree logic inside RSA, therefore they can't currently be visualised. 
