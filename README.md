![Favicon](https://raw.githubusercontent.com/ericwbailey/favicon/readme-assets/project-logo.png)

This is an attempt to capture [all possible favicons](https://github.com/ericwbailey/favicon/tree/master/demo) for a web project, allowing designers to execute pixel-perfect designs for every possible device. This includes considerations for mobile homescreen icons, social media preview images, and pinned operating system tiles, etc.

## Table of Contents

1. [Motivation](#motivation)
- [Installation](#installation)
- [Working](#working)
- [Contributing](#contributing)
- [Additional Resources](#additional-resources)
- [FAQ](#faq)
- [License](#license)

## Motivation

This project arose from working with the excellent [Real Favicon Generator.net](http://realfavicongenerator.net/). Although it is incredibly well-researched and comprehensive, there are certain situations where automatic image scaling and processing does not produce optimal results.

This is especially evident for smaller icons, where the fidelity does not scale well, or when the artboard's width does not allow for a clean, even alignment.

The web may not be pixel-perfect, but icons are. Your icon is integral to recognition of your project, and the best icon your end user will see will be the one their device installs.

## Installation

Either clone or download a copy of this repo:

- `git clone https://github.com/https://github.com/ericwbailey/favicon.git`
- <https://github.com/ericwbailey/favicon/archive/master.zip>

## Working

The included artboards pair with Real Favicon Generator's output, plus [some additional formats that are left off for performance reasons](http://realfavicongenerator.net/faq/#why_some_png_sizes_are_missing). Include these icons only if they are applicable to your project.

### Sketch

`favicons.sketch` contains all artboards for use with [Sketch](http://sketchapp.com/), organized by pages. A Symbols page used to quickly and consistently update background colors (if applicable).

### Illustrator

`favicons.ai` contains all artboards for use with [Illustrator CC](http://www.adobe.com/products/illustrator.html). Symbols are used to reference the different general sizes of icons you may need, although they should be tweaked on a per-artboard level.

Layers prefixed with "NO EXPORT" should have their visibility toggled off before export.

### Photoshop

`favicons.psd` contains all artboards for use with [Photoshop CC](http://www.adobe.com/products/photoshop). Vector-based Smart Objects are used to reference the different general sizes of icons you may need, although they should be tweaked on a per-artboard level.

Layers prefixed with "NO EXPORT" should have their visibility toggled off before export. You can use Photoshop's layer filtering capabilities to make this less tedious.

### Icon Slate

The `.iconsproj` files contain templates for creating `.ico` files with [Icon Slate](http://www.kodlian.com/apps/icon-slate) via the exported PNGs.

### General tips

- Be sure to work with pixel view and zoom to 100% after doing detail work to get a better idea of how the final image will render.
- The grids are sourced from the vendor's recommended grid systems. When I couldn't find a grid template, I defaulted to using the [Chrome Webstore grid](https://developer.chrome.com/webstore/images), since it's pretty flexible—anything that complies with Apple and Android's icon template system will probably work with it as well.
- Use the empty `container` rectangle to proportionately scale an icon's size when copying it to a new artboard.
- Mathematical center is different than optical center, use artboard alignment tools first, then nudge to get your icon into the proper position.
- Some icons don't technically require a transparent background, feel free to add a colored background back in if your logo demands it.
- Remember to hide the grid layer before exporting!

## Contributing

Help and feedback is appreciated! Feel free to [submit a Pull Request](https://github.com/ericwbailey/favicon/pulls) or raise an [Issue](https://github.com/ericwbailey/favicon/issues) here on the repo, or [contact me](https://github.com/ericwbailey/favicon/blob/master/AUTHORS) directly.

## Additional Resources

Proper icon design is *a lot* of work. Here are some links to provide some more guidance with the process:

### Reference

#### Apple

- <https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/IconMatrix.html>
- <http://taylor.fausak.me/2013/11/01/ios-7-web-apps/>
- <http://blog.iconfactory.com/2015/11/the-new-favicon/>

#### Google

- <https://www.google.com/design/spec/style/icons.html#icons-product-icons>
- <https://developer.chrome.com/webstore/images>

#### Microsoft

- <https://blogs.msdn.microsoft.com/ie/2012/06/08/high-quality-visuals-for-pinned-sites-in-windows-8/>
- <https://msdn.microsoft.com/library/dn455106%28v=vs.85%29.aspx>
- <http://hicksdesign.co.uk/journal/pinned-sites-in-windows-8>
- <https://colorlib.com/etc/metro-colors/>

#### Social

- <https://developers.facebook.com/docs/sharing/best-practices#sharing-best-practices-for-websites>
- <https://dev.twitter.com/cards/types/summary>
- <https://dev.twitter.com/cards/types/summary-large-image>
- <https://support.twitter.com/articles/127871#>
- <https://www.facebook.com/help/125379114252045>
- <https://developers.google.com/+/web/snippet/article-rendering>

#### Optional

- <https://dev.opera.com/extensions/effective-icons/>
- <https://dev.opera.com/articles/opera-coast/#icon>

### Approach

- <http://www.creativebloq.com/web-design/10-tips-precise-designing-sketch-41620127>
- <http://www.creativebloq.com/illustrator/create-perfect-favicon-12112760>
- <http://blog.mengto.com/pixel-perfection/>
- <https://bjango.com/articles/icondesignworkflow/>
- <https://bjango.com/articles/everythingisagrid/>
- <https://bjango.com/articles/designingforretina/>
- <http://blog.iconfinder.com/better-icon-design-in-6-easy-steps/>
- <http://vanseodesign.com/web-design/visual-balance/>
- <http://design.tutsplus.com/articles/7-principles-of-effective-icon-design--psd-147>

## FAQ

### Why don't you use just a single vector file?

I wish I could!

### What about pixel grids?

I'm purposely trying to leave the pixel grids loose for this project, and leave that up to the designer's discretion. I figure the the various vendor grids are a good enough starting point.

### What is the circle grid on the logo and avatar artboards?

Certain apps and services will mask the corners of your avatar to make it look like a circle. This grid helps ensures that your favicon looks good in those contexts.

### What's up with the Microsoft icons?

The favicon for pinned sites should have a 1 color treatment to match the Windows Metro style. Ensuring your logo can hold up at one color is also a good practice to make sure it will hold up for things like being printing on merchandise.

### Why are the artboard's image sixes different size than their filenames or specifications?

There are two reasons: 1) Microsoft inexplicably recommends [using a larger image size](https://msdn.microsoft.com/library/dn455106%28v=vs.85%29.aspx) than what their filenames suggest. 2) Social media icons are double the maximum size to ensure only high quality art is used.

### Why don't you reuse the Facebook image for Twitter and Google+?

Each social network requires a slightly different aspect ratio. This ensures your social images aren't improperly cropped or distorted.

### How do I implement this on my site?

Check the [`demo/`](https://github.com/ericwbailey/favicon/tree/master/demo) directory for example images and markup.

### I don't see the icon I'm looking for. What gives?

According to [Real Favicon Generator.net](http://realfavicongenerator.net/), this is the minimum range of icons needed for the maximum amount of support. If you feel like something is missing, feel free to [contribute](#contributing).

## License

[MIT License](https://raw.githubusercontent.com/ericwbailey/favicon/master/LICENSE).
