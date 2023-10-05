## css-hacks
css hacks tricks and solutions for dev

```css
// fix prime ng css issue
* {
  box-sizing: border-box;
}
// remove the default margin for body
body {
  margin: 0;
  padding: 0;
}
// center a container element
.container {
  max-width: 80%;
  margin-inline: auto;
}

// full-width showcase
.showcase_1 {
  margin: -1 !important;
  padding-top: 150px;
  padding-bottom: 150px;

  background-color: rgba(0, 0, 0, 0.5);
  color: #fff;
  background-image: url("assets/bgdark/5166950.jpg");
}
```

## Minimal css properties and value most of the getting start project 

```css
// reset the default margin, If you add any framework don't do this it will overwrite the framework behaviour
* {
    margin:0;
    padding:0;
    box-sizing: border-box;
}
// put light dark color whole page
html {
    color-scheme: light dark;
}
// Minimal design for body text
body {
    font-family: 'Poppins', sans-serif;
    font-size: 1.125rem;
    line-height: 1.6;
    /*background-color: #eaeff1;*/
}
// Center the main containr like: margin:0 auto;
main {
    width: min(65ch,100% - 4rem);
    /* margin: 0 auto; work*/
    margin-inline: auto;
}
// Remove the default style
a {
    text-decoration: none;
    color: #ccc;
}
// Definitely use the below for responsive image style
img,picture,svg {
    max-width: 100%;
    display: block;
    /*object-fit: cover;*/
}
// Remove the default bullet points from the list item
ul li {
    list-style: none;
}
```
