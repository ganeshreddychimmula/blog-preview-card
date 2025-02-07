# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![mobile screenshot](./Screenshots/mobile%20screenshot.jpg)
![computer screenshot](./Screenshots/Screenshot%20(8).png)
### Links

- Solution URL: [https://github.com/ganeshreddychimmula/blog-preview-card.git](github)
- Live Site URL: [https://ganeshreddychimmula.github.io/blog-preview-card/](github pages)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Responsive designs


### What I learned

```css
@font-face {
    font-family: FigTree;
    /*
    Yes, when using @font-face, the font-family value 
    (which defines the name of the font) should be enclosed in quotes if it contains multiple words, 
    but it’s not strictly required if it's a single word.
    */
    src: url("./assets/fonts/Figtree-VariableFont_wght.ttf") format("truetype-variations");
    /*
    The format("truetype-variations") value in the @font-face src declaration is used for variable TrueType fonts (TTF) 
    that support multiple weights, widths, and styles in a single file.
    Used for browsers that natively recognize variable fonts in truetype format.
    Some browsers can detect that the file contains variations just from truetype-variations.
    If a browser does not support this format, it will skip this declaration
    */
    src: url("./assets/fonts/Figtree-VariableFont_wght.ttf") format("truetype") tech("variations")
    /*
    Explicitly tells the browser that this is a ttf font with variations.
    Some browsers recognize format('truetype') but require tech('variations') to enable variable font features.
    Ensures better support across different implementations of variable fonts.
    Acts as Fallback Mechanism: If a browser doesn't understand truetype-variations, it might still process truetype with tech('variations').
    */
}
```

-> using custom variables for certain properties helps maintain consistency
```css
:root{
    --yellow: hsl(47, 88%, 63%);
    --white: hsl(0, 0%, 100%);
    --light-gray: hsl(0, 0%, 42%);
    --dark-gray: hsl(0, 0%, 7%);
}

```


-> Keeping class names relevant to parent class name is important
