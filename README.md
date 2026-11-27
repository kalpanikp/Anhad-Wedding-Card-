# Anhad & Toshi · Anand Karaj invite

Scroll-driven Gurdwara invitation (mobile-first): native page scroll plays the film; sections reveal as you scroll.

## Edit the details
Open `index.html` and change the `INFO` block near the top of the script:
names, parents, start/end time (drives the date on the card, countdown and calendar), time wording, venue, city,
Google Maps search text, and the WhatsApp number for confirmations (`rsvpPhone`, country code, no +).
Set `preview: false` to remove the "preview" label.

## Files
- `a/open.mp4`: card opening (plays on first tap; loads first)
- `a/j/000–351.webp`: the whole camera journey at 12 fps (540×960), built straight from the source clips; frames near the camera are kept GPU-ready while dragging
- `a/hd/1–4.webp`: full-resolution stills shown whenever the camera comes to rest
- `a/*.mp3`: Ik Onkar music bed, ambiences and sound effects
- `a/f2/`: fonts (Cormorant Garamond, Cinzel, Noto Serif Gurmukhi), self-hosted
