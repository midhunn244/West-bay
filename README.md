# West Bay Palm Tree Beach Resort - Demo Website

Static site (no build step). Deploy on Vercel: drag this folder into vercel.com/new, or run `vercel` in this folder.

## Files
- index.html : whole website (HTML, CSS, JS)
- images/room.jpg, sea.jpg, pool.jpg : placeholder photos. Replace with the resort's own photos (keep the same file names, lowercase).
- vercel.json : Vercel settings
- standalone/index.html : single-file version with images embedded (works offline)

## Before going live
- Replace placeholder photos (sea.jpg has a third-party watermark, "ARUN PHOTOS"; use licensed/own photos).
- Resort must confirm: facilities, room descriptions and photos, distances, phone, review link, and permission to show the reviews.
- Map: the Location section embeds Google Maps by name and address. For the exact pin, open the resort on Google Maps > Share > Embed a map, and paste that src into the iframe in index.html.
- Remove the demo banner and footer disclaimer after approval.
- Rates are intentionally not shown.
