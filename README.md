# <image src="https://what3words.com/assets/images/w3w_square_red.png">&nbsp;w3w-glyphicon

This repo shows how to display a 3 word address with the square logo

This sample is visible live here https://what3words.github.io/w3w-glyphicon

## Content
This sample is composed of an `index.html` page, using a `css` which is including the fonts from the `fonts` folder

```
.
├── css
│   └── w3w-glyphicon.css
├── fonts
│   ├── w3w-grid.eot
│   ├── w3w-grid.svg
│   ├── w3w-grid.ttf
│   ├── w3w-grid.woff
│   └── w3w-grid.woff2
├── index.html
```

## How to use

what3words font contains the square icon and can be used inline text with
```html
<i class="glyphicon-w3w">&#xe800;</i>
```

The `glyphicon-w3w` class is defined below:

```css
@font-face {
    font-family: "w3w-grid";
    src: url("../fonts/w3w-grid.eot");
    src: url("../fonts/w3w-grid.eot#iefix") format("embedded-opentype"),
    url("../fonts/w3w-grid.woff") format("woff"),
    url("../fonts/w3w-grid.ttf") format("truetype"),
    url("../fonts/w3w-grid.svg#w3w-grid") format("svg");
    font-weight: normal;
    font-style: normal;
}

.glyphicon-w3w {
    font-family: "w3w-grid";
    font-style: normal;
    font-weight: normal;
    speak: none;
    display: inline-block;
    text-decoration: inherit;
    width: 1em;
    margin-right: .2em;
    text-align: center;
    /* opacity: .8; */
    /* For safety - reset parent styles, that can break glyph codes*/
    font-variant: normal;
    text-transform: none;
    /* fix buttons height, for twitter bootstrap */
    line-height: 1em;
    /* Animation center compensation - margins should be symmetric */
    /* remove if not needed */
    margin-left: .2em;
    /* You can be more comfortable with increased icons size */
    /* font-size: 120%; */
    /* Font smoothing. That was taken from TWBS */
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
```

#### Changing the icon font location
font files are located in the ../fonts/ directory, relative to the CSS file. Moving or renaming those font files means updating the CSS.

## LICENSE

MIT
