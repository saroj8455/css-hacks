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
// reset the default margin, If you add any framework
// don't do this it will overwrite the framework behaviour
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
## Minimal css for button and paragraph only show limited line
```css
// Center the button text or button
button {
    border: none;
    padding: 1rem 1.5rem;
    border-radius: 50px;

    font-weight: 600;
    color: #0077ff;
    background-color: #e0efff;
/*    button is an inline-block element by default,
it needs to have a block display for margin: 0 auto; to work */
    display: block;
    margin: 0 auto;

    cursor: pointer;
}
// Display only 3 lines of a paragraph or description
// Like: hi hello world...
.card__text {
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-line-clamp: 3;
    overflow: hidden;
}
```
//Contribute from OCEM , BLGR 