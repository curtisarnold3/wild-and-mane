# Wild & Mane — homepage

One static file (`index.html`) plus an `images/` folder. No build step. Fonts load from Google Fonts (Barlow Condensed, Lora).

## Deploy
Push this folder to a GitHub repo and turn on GitHub Pages (Settings → Pages → deploy from branch). Done.

## Theme
"Wild and free." High-plains palette: dust `#E7E0D1`, storm `#23292E`, saddle `#6B3A1F`, sage `#6F7D62`, sky `#C4D1D8`, bone mat `#F4F0E7`. Display type Barlow Condensed (rodeo-program condensed gothic), body Lora.

## Placeholders to fill
Search for `[` in index.html: [TOWN], [COUNTY], [CAMERA], [HORSE NAME], [PHOTOGRAPHER FIRST NAME], [YEAR], [Print title], [Edition title], [X], [25], [SIZE], [DATE], [PRICE], [ETSY SHOP URL], [EDITION URL], [INSTAGRAM URL], [PINTEREST URL], [SHIPPING PAGE URL], [EMAIL], [EMAIL FORM ACTION].

Prices in the "See it on your wall" tool live in the `prices` object at the bottom of index.html. $38 unframed 11×14 and $119 framed are from the business plan; the rest are [PRICE].

## Images
The 12 brand photos are the same CC0 stand-ins used in the first mockup (Wikimedia Commons, mostly originally Unsplash), named by role: golden, bw, boots, sisters, p1–p4, edition, about1, about2. Replace each with her photo of the same name.

`images/wall.jpg` is the room behind the "See it on your wall" preview: "At Home (Unsplash)" via Wikimedia Commons, CC0, with the picture that was hanging there painted out. If you swap the room photo, re-tune the `.print` position and the size percentages in the CSS (they assume a 78-inch sofa at 63% of the photo width).