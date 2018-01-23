### DAY 12 SPA'S    (WE MISSED MLK DAY)

## URL and Routing
"request parameters" replace "query string parameters"
this is a layer onPopState.

Client side routing
-faster and updates the contents of A SINGLE PAGE APP.

controller in a web app ... MAPS INCOMING HTTP URL REQUEST TO A PARTICULAR HANDLER (handler = controller)
PULL THE DATA FROM THE DATABASE AND PUSH IT INTO THE TEMPLATE.

...www.cf.org/blog.html  - old school
...www.cf.org/blog/      client side routing

use the request parameters to only get the items to be rendered to you want
get: /
get: /articles
get: /articles/42
push: /articles/42/edit
get: /articles/42

Controller handles the user request
simply a list of functions (aka: actions)
!! One controller per resource. !!!


page.js syntax
page('/', user.list)

history.pushState can use objects within history.

page('/user/:user/edit', edit)

:matches 


grab the CDN for pages.js


**** notfound

## Anatomy of a URL



## INTRO to PAGE.JS


## Let's Build a SPA



* on Project Week! DEPLOY THE APP!!!


#### walk through 

1st party modules( node.js )
    * Node.js has built-in modules
3rd party modules

app = express

process.env.PORT  enviroment variables  (config vars in HEROKU)

create your middleware

app.listen at the bottom



keep app.listen files


*brew install tree



in the MVC model 

Model is going to hold data  i.e. .json file

Controller  -  put all of the page.js code that grabs the code
            - about, contact, home js files  

Views  -    aboutView.js
            contactView.js
            homeView.js

always put jQuery 


Logic intergration

app.use(express.static('./public'));
app.use is rout level middleware

app.get('*', (req, res) => {
    res.sendFile('index.html', { root: 'public'});
});