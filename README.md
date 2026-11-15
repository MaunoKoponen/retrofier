# Retrofier

**Turn any image into a retro game screen, CRT monitor, or pulp magazine print — entirely in the browser.**

A single-file, zero-dependency, fully client-side tool for real-time image stylization. Drop in a picture, tweak the controls, and instantly see the result.

No server, no build step, no accounts. Just open the HTML file.

## Features

- **Pixelation / Rasterization** — nearest-neighbor scaling with adjustable pixel size
- **Authentic palettes** — Game Boy, Game Boy Color, CGA, EGA, VGA 16/256, Amiga, Atari ST, Macintosh, Pico-8, and more
- **Floyd-Steinberg dithering**
- **Horizontal & vertical scanlines**
- **CRT effects** — barrel curvature, chromatic aberration, glow, and vignette
- **Pulp magazine print** — halftone dots, limited ink palette, paper texture, and color misregistration
- **Full ASCII system** — multiple character sets, color ASCII, independent density controls, invert
- **Real-time preview** — every change updates instantly
- **100% local** — images never leave your device

## Quick Start

1. Download [`retrofy.html`](retrofy.html) (or clone the repo)
2. Open it in any modern browser (Chrome, Edge, Firefox, Safari)
3. Drop an image or click **Choose file** (Note: for the first image, time the drag and drop might not work properly)  
4. Play with the controls
5. Use mouse right click -> "save image as.."

That’s it.

## Controls Overview

| Section       | What it does                                      |
|---------------|---------------------------------------------------|
| Pixel scale   | Controls the size of the retro pixels             |
| Palette       | Classic hardware and print color sets             |
| Scanlines     | Horizontal and vertical CRT-style lines           |
| CRT           | Curvature, chromatic aberration, glow, vignette   |
| Pulp Print    | Halftone screening + paper simulation             |
| ASCII         | Text rendering with multiple styles and color     |

## Palette Highlights

- **Handhelds**: Game Boy, Game Boy Color  
- **Early PCs**: CGA, EGA, VGA 16-color, VGA 256 (approx)  
- **Home computers**: Amiga, Atari ST, Macintosh  
- **Print**: Pulp Ink  
- **Other**: Pico-8, monochrome, sepia, custom bit depth  

## Technical Notes

- Pure HTML + CSS + JavaScript
- No frameworks, no build tools, no external dependencies
- All processing happens on the canvas in the browser
- Works offline after the first load
- Image data stays on your machine

## Browser Support

Works in all modern browsers with canvas support.  
Best experience on Chrome / Edge / Firefox.

## License

MIT — free to use, modify, and share.

## Contributing

Well why not if you want to! Ideas for additional palettes, CRT options, or print styles are especially appreciated.

---

Made for anyone who loves the look of old screens and cheap pulp paper.
