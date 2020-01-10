# mericons
A mix of Fontawesome 4.7, Icomoons, Simpleicon and some custom icons.

The *SVG* folder contains the icons.

*demo.html* lists the icons. To insert your icons as inline SVGs (with the <use> element), copy the <svg> element (that contains symbol definitions) from the source of the demo.html file, below your own HTML's <body> tag. After copying this SVG, you can reference your glyphs like the following:

```
<svg class="icon mer-px"><use xlink:href="#mer-px"></use></svg>
```

You can get this code from the SVG tab of the IcoMoon app, or by referring to the source of the demo.html file. To see how you can change the color/size of your icons using CSS, refer to the example provided in the *style.css* file.

If you prefer to reference an external SVG (containing <defs>) instead of embedding it in HTML, you will need to use *svgxuse.js* in order to support IE 9+. In browsers that don't support referencing external SVGs (such as IE 9), this polyfill sends one HTTP request to fetch and cache all symbol definitions. See *demo-external-svg.html* for this approach. This demo references the *symbol-defs.svg* file and uses the aforementioned polyfill. Note that it must be hosted on a web server to work
properly. Learn more about this polyfill here: https://github.com/Keyamoon/svgxuse

You can import *selection.json* back to the IcoMoon app using the *Import Icons* button (or via Main Menu → Manage Projects) to retrieve Mericons mix.

