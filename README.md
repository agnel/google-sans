# Google Sans

The CSS and font files to easily self-host the "Google Sans" font.

## Quick Installation

This package has a variety of methods to import CSS, such as using bundler like Webpack. Alternatively, it supports SASS.

```javascript
npm install github:agnel/google-sans
```

Within your app entry file or site component, import it in.

```javascript
import "google-sans"; // defaults to weight 400.
```

Supported Varialbes:

- Weights: `[400, 500, 700]`
- Styles: `[italic, normal]`
- Supported subsets: `[armenian, cyrillic, devanagari, georgian, greek, gurmukhi, hebrew, lao, tamil, thai, vietnamese, latin-ext, latin]`

Finally, you can reference the font name in a CSS stylesheet, CSS Module, or CSS-in-JS.

```css
body {
  font-family: 'Google Sans'
}
```

## Licensing

It is important to always read the license for every font that you use.

See: [Google Restricted](https://fonts.google.com/license/googlerestricted)

## Other Notes

Font version (provided by source): `v41`

Feel free to star and contribute new ideas to this repository that aim to improve the performance of font loading, as well as expanding the existing library. Any suggestions or ideas can be voiced via an [issue](https://github.com/agnel/google-sans/issues).