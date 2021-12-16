
# Metalsmith branding

A branding set of SVG's, PNG's, and iconfont for metalsmith.  
SVG's with a `-web` suffix have the `fill:currentColor`, so they can easily be changed by specifying `color` on a parent element.

## Installation

```
git clone https://github.com/metalsmith/branding.git
npm install
```

## Usage

Use [`icons/view.html`](icons/view.html) to find a suiting icon for your plugin.
Use [`images/view.html`](images/view.html) to see all available images.
Use any of the images for your metalsmith-related blog posts, pipeline process avatars, or presentations.
The `images/svg/inline` are for developers, and have `fill` set to `currentColor`.

### For developers

View & search metalsmith icons
```
npm run view:icons
```

View & search metalsmith logo variants
```
npm run view:images
```

The [`images/icon`](images/icon) files are generated with [realfavicongenerator](https://realfavicongenerator.net) from the `source.svg` file.

## License 

This repository is licensed under [MIT](LICENSE), however the individual images are CC-BY-SA.
You are free to use them in any way you see fit, but please do not republish them in non-metalsmith-related contexts.
