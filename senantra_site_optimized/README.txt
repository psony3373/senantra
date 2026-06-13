SÉNANTRA optimized site package

Files:
- index.html                 : Gate/homepage
- senantra-homepage.html     : Alias copy of homepage for old links
- lighthouse.html            : Lighthouse page with fixed Return to the Gate link
- assets/                    : Externalized optimized visual assets

Fixes:
- Return to the Gate now points to index.html.
- Large Base64 raster images were extracted from HTML and converted to WebP assets.
- Fog image is externalized as assets/fog-effect.webp.
- Transition sequence in lighthouse.html is preserved from the supplied file.

Upload these files together, keeping the assets folder next to the HTML files.
