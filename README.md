# Kaala Mithra — Email Marketing webpage

This folder contains the complete Email Marketing webpage and its editable source project.

## Open the webpage

Open `index.html` in a modern browser. It is a self-contained build with its CSS, fonts, logo, and imagery embedded, so it does not need an internet connection or a web server to display.

## Included project files

- `index.html` — current ready-to-view webpage
- `index.src.html` — editable HTML source
- `theme.css` and `fonts.css` — page styling and embedded fonts
- `assets/` — logo and original illustrative campaign/service images
- `build.py` — rebuilds the standalone `index.html` from the source and assets
- `qa.py` — static checks for page content and links

## Rebuild and check

From this directory, run:

```bash
python3 build.py
python3 qa.py
```

The build script uses Pillow (`PIL`). Install it with `python3 -m pip install Pillow` if it is not already available.

## Contact and visuals

The page's direct email button opens a message to `kaalamithra.sales@gmail.com`; WhatsApp and phone links use `+91 63618 42299`. The page has no enquiry form or submission storage. All campaign and service images are illustrative concepts, not client work.
