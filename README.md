# Trianglify Background Generator

![](app.png)


Trianglify Background Generator is a web tool for creating beautiful SVG-based backgrounds using the [Trianglify](https://github.com/qrohlf/trianglify) library. It supports color palettes from [ColourLovers](https://colourlovers.com) and [ColorBrewer](https://colorbrewer2.org/).

## Live Demo
See the app in action: [Demo](http://alssndro.github.io/trianglify-background-generator/)

## Features
- Generate SVG backgrounds with customizable cell size, padding, bleed, and gradients
- Choose from top 100 ColourLovers palettes and ColorBrewer palettes
- Download generated backgrounds as PNG images

## Installation
This project is static and requires no build step. Simply clone and open `index.html` in your browser.

```
git clone https://github.com/alssndro/trianglify-background-generator.git
cd trianglify-background-generator
open index.html
```

## Usage
1. Adjust render options (width, height, cell size, padding, bleed)
2. Select a color palette and gradient direction
3. Click "Regenerate" to update the background
4. Click "Download" to save the image as PNG

## Dependencies
- [Trianglify](https://github.com/qrohlf/trianglify) (uses D3.js v3)
- [jQuery](https://jquery.com/) (currently v1.11.0, consider updating to v3+)
- [jQuery UI](https://jqueryui.com/) (currently v1.10.4, consider updating to v1.13+)
- [D3.js](https://d3js.org/) (currently v3, consider updating to v7+ and Trianglify v4+)
- [Normalize.css](https://necolas.github.io/normalize.css/)

## Browser Support
- Chrome (recommended)
- Firefox
- Edge
- Safari (Download feature may not work due to SVG/Canvas limitations)

## Known Issues
- Download feature does not work in Safari due to SVG-to-PNG conversion limitations
- Noise slider is omitted to prevent browser crashes with large SVGs
- Uses legacy versions of libraries; updating is recommended for security and performance

## Recommendations for Modernization
- Update all external libraries to their latest versions and use HTTPS links
- Refactor JavaScript to use ES6+ features (`let`, `const`, arrow functions, etc.)
- Consider using npm/yarn for dependency management
- Add accessibility improvements (ARIA, keyboard navigation)
- Add favicon and manifest for PWA support

## Contributing
Pull requests are welcome! Please open issues for bugs or feature requests.

## License
MIT
