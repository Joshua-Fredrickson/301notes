## day 7

### node.js
node is not a browser based tool.
event-driven i.e. event emitter module
non-blocking I/O model -> we can interact with a data and deconstruct it down to binerary. 
    -> this is also asynchronous model.
*it's single threaded model (that has a call back que)
It's great for our API development and command line I/O.
learnyounode.com

node is built into the terminal!!!!
>this = the global object on the computer!

*** caveats with ES6 


### npm - node packet manager
check out npm website to find out about packages (and then it checkout on GitHub)
the packages are like a library

NODE.JS project:
create an empty director:
type npm that gives you the manual page


npm init -> it walks you through a prompt that creates a package.json file that is at the root of all web app.

npm init -y creates a blank package.json file (meta info)

npm install (or npm i) -S express (or --s)
anytime you install a new module "node_modules" dir

when you add a dependency NPM adds or remove the dependency in the package.json file
-g flag allows you to install anywhere on my computer.
We will git ignore the node Modules

-We can have dependency hell... depending on what dependencies we add


cowsay is a test module

ls -a
.gitignore
checkout: gitignore.io
use on the website:  macOS (to remove the DS.Store), Node, linux, windows


### express.js

API (application programming interface)
(data or methods)

!!!! Make a basic Server !!!!
to make an api :)

1. make a dir
2. create a git repo
3. npm init -y
4. create a server file  touch server.js *only to be used to make
5. npm i -S express
6. open server.js 
    -   add 'use strict';
    -   add dependencies
    -   const = defines a constant
    -   add: const express = require('express');  (old school way)
    -   add: const app = express();   *these are per expresses documentation.
    -   add: const PORT = process.env.PORT || 3000;   *env is environment 
    -   add: appl.listen(PORT, () => {
                console.log('currently listening on PORT');
            })   

to run the file, "node server.js"

we have created a local server!

            *backend tends to be

create endpoint 
    -   app.get ('/api/resource, (req, res) => {         
        res.status(200).send('you just made a request!');
    }):

    on the browser, you can use "localhost:[port]" 


    control

    curl is Command Line URL


manually kill and restart server when we are making adjustments!!!!!!!!!!!!!!!!!


### asignment prep

check out the express docs on how to create a 404

each person needs to add "npm i" after the scaffolding.