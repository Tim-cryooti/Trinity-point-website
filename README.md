# Trinity Point Landscaping website

The site at trintypoint.com. Brush clearing and landscaping, Hudson Valley, NY. Call or text 845-718-1328.

- `index.html` is the whole page (styles and scripts included).
- `assets/` holds the logo, photos and background videos.

Netlify deploys this repository automatically whenever `main` changes.

## Instant quote (brush clearing)

- The "Your price in 60 seconds" section and its full-screen quote flow live in `index.html` (search for `Instant quote`).
- Prices come from the `PRICE` block at the top of the quote script. Change the numbers there to change what customers see.
- Every lead goes to Netlify Forms (form name `quote`) at four moments: `started` (name + phone entered), `quote` (saw the price), `booked` (asked for a walk-through) and `left` (left before seeing a price). Turn on form detection and email notifications in Netlify for these to reach the inbox.
