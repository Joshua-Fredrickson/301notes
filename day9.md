#day 9

Schema Models

database design structure
relational databases management systems  -quickly create


### USER MODEL

USER                PROFILE
-username           -username
-email              -email
-password           -profile.pic
                    -description

user--> profile (usually not the other way around)                    
##### Yesterday DEMO

in node_modules, Dev dependencies help with creating tests.

packages
meta info 
install server
test server
create routes
to static files(non functioning)
to DataBase (non functioning)
creating the HTML
create the .js logic on the web site.
create a function to create a table in SQL


check out "test frameworks"!!!!
mocha & chia.js

Describe blocks

expect blocks



social media agrigation app that gathers all the data from FB #insta etc... and combines it into your app.


check out APIs!!!!!  
CORS issues can black list ips 

### SQL - JOINS and RELATIONSHIPS!
check out the relational model in wiki
Data Models Schema


ENDPOINTS!!!
/api/cats   cats is the resource

/api/weather/seattle   weather/seattle = uri
uniform resoure indicator

normalization - discussion this 
in creating databases & make them scalable and make it modulize it!

Checkout SQL aliases.

NO SQL systems are out there.

### FUNCTIONAL PROGRAMMING
this is a paradigm!

SIMPLE != EASY
You can easily chain 
FP methods
.forEach
.some and .every
.concat

Defanition of FP
- Immutablity
- Declarative vs. Imperative code
- stateless (pure) funciotns
- First class functions & currying

FP does not mutate or change the original data.
check out the following immutability in JS
ImmutableJS, Mori, Deep-freeze


.map
to run a function through each array and returns a new array.

.filter
it's an array method that passes a logic and then creates a new array

.reduce
it accepts callback function that creates an object or an array.
it can also create an object with {} after you pass the call back.

example:

RETURN OBJECT
var stuff = ['pencil', 'pen']

stuff.reduce (function(acc, cur, idx, arr) {
    acc[cur] = cur.split('').reverse().join('');
},{});


acc | cur       | idx   | arr    | result
--------------------------------------------
{}  | 'pencil'  | 0     | [..]   | { pencil:'lincep}


accumulator = acc
current = current







LAB HINT = indexOf keeps 1 item.


iife
immediately invocated function expression
This gives us private helpers for globally expression that are in a private scope.


MOST IMPORTANT  WRRC & FP of this week!!!!!