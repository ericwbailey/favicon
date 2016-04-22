![favicons](https://raw.githubusercontent.com/ericwbailey/favicons/master/examples/logotype.png)

This is an attempt to capture [all possible favicons](https://github.com/ericwbailey/favicons/tree/master/examples) for a web project, allowing designers to execute pixel-perfect designs for every possible device. This includes considerations for mobile homescreen icons, social media preview images, and pinned operating system links, etc.

## Table of Contents

1. [Motivation](#motivation)
- [Installation](#installation)
- [Working](#working)
- [Contributing](#contributing)
- [Additional Resources](#additional-resources)
- [Attribution](#attribution)
- [License](#license)

## Motivation

This project arose from working with the excellent [Real Favicon Generator.net](http://realfavicongenerator.net/). Although it is incredibly well-researched and comprehensive, there are certain situations where automatic image scaling and manipulation does not produce optimal results.

This is especially evident for smaller icons, where the fidelity does not scale well, or when the artboard's width does not allow for an clean, even alignment.

The web may not be pixel-perfect, but icons are. Your icon is integral to recognition of your project, and the best icon your end user will see will be the one their device installs.

:japanese_goblin: *Yes, I know that the demonstration icon doesn't exemplify this, I'm working on it!*

## Installation

Either clone or download a copy of this repo:

- `git clone https://github.com/https://github.com/ericwbailey/favicons.git`
- <https://github.com/ericwbailey/favicons/archive/master.zip>

## Working

`favicons.sketch` contains all artboards, while the `.iconsproj` files contain template for creating `.ico` files with [Icon Slate](http://www.kodlian.com/apps/icon-slate) via the exported PNGs. `favicons.sketch` is organized by pages, with a Symbols page used to quickly and consistently update background colors (if applicable).

The included artboards pair with Real Favicon Generator's output, plus [some additional formats that are left off for performance reasons](http://realfavicongenerator.net/faq/#why_some_png_sizes_are_missing). Include these icons only if applicable to your project.

Some general tips:

- Be sure to work with pixel view and zoom to 100% after doing detail work, to get a better idea of how the final image will render.
- The grids are sourced from the vendor's recommended grid systems. When I couldn't find a grid template, I defaulted to using the [Chrome Webstore grid](https://developer.chrome.com/webstore/images), since it's pretty flexible—anything that complies with Apple and Android's icon template system will probably work with it as well.
- Use the empty `container` rectangle to scale an icon's size up/down consistently.
- Mathematical center is different than optical center, don't rely too heavily on artboard alignment tools.
- Some icons don't technically require a transparent background, feel free to add a colored background back in.
- Remember to hide the grid layer before exporting!

## Contributing

Help and feedback is appreciated! Feel free to [submit a Pull Request](https://github.com/ericwbailey/favicon/pulls) or raise an [Issue](https://github.com/ericwbailey/favicon/issues) here on the repo, or [contact me](https://github.com/ericwbailey/favicons/blob/master/AUTHORS) directly.

## Additional Resources

Proper icon design is a lot of work. Here are some links to provide some more guidance with the process:

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

#### Optional

- <https://dev.opera.com/extensions/effective-icons/>
- <https://dev.opera.com/articles/opera-coast/#icon>

### Approach

- <http://www.creativebloq.com/illustrator/create-perfect-favicon-12112760>
- <http://blog.mengto.com/pixel-perfection/>
- <https://bjango.com/articles/icondesignworkflow/>
- <https://bjango.com/articles/everythingisagrid/>
- <https://bjango.com/articles/designingforretina/>
- <http://blog.iconfinder.com/better-icon-design-in-6-easy-steps/>
- <http://vanseodesign.com/web-design/visual-balance/>
- <http://design.tutsplus.com/articles/7-principles-of-effective-icon-design--psd-147>

## Attribution

- The demonstration [Japanese Goblin Mask](http://emojipedia.org/japanese-goblin/) logo comes from the [EmojiOne](http://emojione.com/) project.
- Artboard selection and sizes come from [Real Favicon Generator.net](http://realfavicongenerator.net/)

## License

[MIT License](https://raw.githubusercontent.com/ericwbailey/favicons/master/LICENSE).
