## SCSS Modules

All about SCSS!

### SASS EXERCISES!

### VARIABLES

1) Code the below layout. The border-radius of all the boxes and buttons are 2px. Use variables wherever necessary.

Background Color- #205564


<img width="801" alt="screen shot 2017-08-01 at 11 49 21 pm" src="https://user-images.githubusercontent.com/25129851/28834570-2a8eaf36-7715-11e7-8bb6-8a0ee6b17602.png">

2) Code the below layout.  The border-radius of all the boxes and buttons are 2px. Use variables wherever necessary.

- Background Color- #1A223F
- The pink color hex code - #E42B74

  Font Sizes: 

- H1 for header(40px)
- Body Text (14px)


<img width="797" alt="screen shot 2017-08-02 at 12 27 57 am" src="https://user-images.githubusercontent.com/25129851/28835875-7786de0e-7719-11e7-8099-75eb076bba5c.png">

### NESTING

1) Code the below navbar. Make use of nesting techniques.

Navbar Colors:
- Background - #E5E5E5
- Text - #000000

<img width="789" alt="screen shot 2017-08-02 at 6 32 38 am" src="https://user-images.githubusercontent.com/25129851/28850016-a28f6318-774c-11e7-8ebb-e921de09c64f.png">


###IMPORTS AND PARTIALS

1) Update your Sass structure to look something like the one below;

  sass
    
      _base.scss
      
      _links.scss
      
      _header.scss
      
      _footer.scss
      
      _info.scss
    main.scss
    
   - Move ALL styles from main.scss to more modular / organized locations.
   - Update main.scss to @import your new partials.
   
###EXTEND

- Create a placeholders partial in your base directory and @import it in your main .scss file.
- Create a placeholder for %clearfix and @extend it on the appropriate selectors.
- Also remove the .clearfix class from the markup(if using bootstrap).
- Create a .navlist class like the one below.

```
  .navlist--inline {
  list-style-type: none;

  li {
    display: inline-block;
  }

  a {
    display: block;
  }
}
```
- @extend that class on elements that match the pattern.

