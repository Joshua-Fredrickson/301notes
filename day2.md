#  Day 2 - jQuery and the DOM
### Code Review
read every line of code!
resubmit labs on your own


### Gitflow Review
our lab repo lives in our organization
fork a direct copy into my git hub account
(settings add a collaborator that can push and pull content)
clone a repo into your local machine
push pull back to local fork
make a pull request back into the organizations lab repo.


### Agile Development
"lack of process over people and tools" -BN
Agile process
old processes:
waterfall process - first come first serve

- agilemanifesto.org
- SCRUM
- add defect remediation time
- Sprints are usually 2 weeks
- backlog
- storyboarding
- burndown charts
- sprint retrospective
- stand up meeting
- pair programming
- User stories template
- READ LEAN Startup

### M.V.C (this is a pattern)
!modularzation!
MODEL VIEW CONTROLLER - super important!
- a design pattern (architecural) for organizing your code
   
- M -   Model : Source Material or Data
- V -   View : Presentation Scheme * .css
- C -   Controller : Behavior management *.js

Benefits:  
Code at a higher level of abstraction
Organize your code base
Leverage best practices

Challenges
learning curve
Inter-file spaghetti code
Hard to extend when the metaphor fails

front end frameworks

Ember.js
Angular.js
Backbone.js
React

** check out two way binding

### The DOM Review
the DOM is a tree structure

##### DOM traverse, manipulate, and selection


### jQuery 101
go to jQuery.com
CDN = content delivery network

jQuery returns an array of jQuery object
Don't use jQuery as coding tool!

going to use .clone today
remove class?
toggle class?
use data attributes!!

do not use jquery to remove and adding classes


Use jQuery is used for selecting, manipulation, and traversing the DOM

don't use .css to change
when you want to apply CSS changes, don't change it through the DOM! Change it through CSS

a jQuery

$newArticle = the $ denotes a jQuery object.

### Assignment Prep

side project build an accordion menu
USE The .on('click',)
not .click();


HTML attribute "data" is arbitrary

i.e. <p data-animal ="mouse"></p>

$('p').data('animal');
<!-- this will return 'mouse' -->

check out "class" for template

<img src = "tshirt.png" data-id = "sku788787">


checkout "for in" loop.

video: @ 4:44pm