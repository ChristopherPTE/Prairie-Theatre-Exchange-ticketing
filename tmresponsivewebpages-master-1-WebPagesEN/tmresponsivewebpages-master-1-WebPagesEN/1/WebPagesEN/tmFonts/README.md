# Fonts

This folder can be used to download fonts for use with CSS (including PDFs).

For PDF compatibility make sure to use True Type Fonts.

## Adding Fonts

1. Create font face CSS file in a file like `tmFonts/myfont.css`

```css
/* Verdana */
@font-face {
   font-family: MyFont;
   src: url('../tmFonts/myfont.ttf');
}

@font-face {
   font-family: MyFont;
   src: url('../tmFonts/myfont-bold.ttf');   
   font-weight: bold;
}

@font-face {
   font-family: MyFont;
   src: url('../tmFonts/myfont-bold-italic.ttf');
   font-weight: bold;
   font-style: italic;
}
```

2. Add reference to `tmFonts/myfont.css` to:
    * `tmScripts/themeCDN.html`
    * `tmScripts/themeLocal.html`
    * `tmScripts/PDFstyles.html`


```html
<link href="tmFonts/myfont.css" rel="stylesheet" type="text/css"/>
```
