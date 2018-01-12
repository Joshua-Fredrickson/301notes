# DAY 4

### Code Review:
- With errors, check the source script & stylesheet links.
- "let" is a kinda like "var" (let is blocked scoped)  lexical function
- article.js is Model in MVC
- articleView.js is Veiw in MVC
- in an interview use ES5 concatenation

* use "let" instead of "var" from now on.

* Checked out open source project and try to contribute

### typography
- typographical elements
(learn how to build a font on You Tube)
make sure your fonts are scalable to any viewport.
xscope tool was for pixel perfect design to development
pixels are static...  px
Ems are kinda scalable... %, em, rem


VW (viewport width)... 1vw = 1% of the viewport width ------ use this

VH (viewport height)... not really used
don't go below 10 px

Check out the Typographic Scale and Golden ratio


chek out SVG fonts
check out @font-face
web fonts

### HTML TEMPLATING
Handlebars.js
tryhandlebars.js
CRUD app

handlebars is a library, compile and render


### Lexical arrow functions - aka fat arrow function
()=>

##### ES5

function logger(input) {
    console.log('my input', input);
}

logger('the thing i want to log');


##### ES6  with lexical arrow functions

let logger1 = (input) => console.log('my input:' input);
variation
let logger2 = input => console.log('my input:'; input);   - only for 1 parameter


$('el').on('click', () => {

});

* RFC  Request for comments are the "real" documentation
* you can lock people out from zooming in on a website.




Lab notes - 

HANDLE BARS COMPLIER - script tag go into the <head> with a "<script id="article-template" type="x-handlbars-template">
need to add more info into the template than what was in the previous lab.

grab the property names and give them {{name}}    

in handlebars...
text needs {{}}
html needs {{{}}}

to find all of the methods in handlebars by using the console and "handlebars."

return template(this);


? turn (area?) error operator logic operator.