# Photo folders

Drop image files (`.jpg`, `.jpeg`, `.png`, `.webp`, `.gif`) directly into:

- `img/hiking/` — shows up in the "Hiking & Climbing" gallery on outdoors.html
- `img/photography/` — shows up in the "Photography" gallery on outdoors.html

No HTML editing needed. The page fetches the folder listing from GitHub at
load time and builds the gallery automatically, in filename order.

Captions are generated from the filename, so name files descriptively:
`white-mountains-summit.jpg` becomes the caption "White Mountains Summit".

After uploading, just commit and push (or upload via the GitHub web UI) —
the live site picks up new photos on the next page load, no rebuild needed.
