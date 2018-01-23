## Day 10

npm module called faker that has a ton of fake data.

addy osmani - javascript design patterns website 

Deployment platforms  i.e. github.io
for Heroku (deployment platform) enable auto deployments

We can provision a DB

Create a PIPELINE for a STAGING and PRODUCTON Code.

Web Hook.... hooking up Heroku to update when github.io


Comment out this mornings code!
were a method is defined and where it is called

## HEROKU pipeline

 Staging  -> Production
 *you need a separate server for frontend and backend servers

 on Heroku you can Automatic Deploys (check it for the staging and not on production)


no pipline for the books app.


*load balancer (this will divide up how many users are on different servers)



### Deploy the Backend
* setup an account on HEROKU

1. mkdir deploy directory
2. make a server directory
** npm i -S cors
app.use(cors());

--- server.js, package.json

3. make a client directory
--- app.js, index.html


4. go into GIT HUB and create an Organization
-do this through settings
-create a repo for server & client
--git init
--- git remote add origin [git url]
-- invite member (click on the private lock)

5. ls -a add a .gitigonore file (a part of scaffold!)
6. ACP github
7. IN HEROKU - create a new app
8. connect to Github organization
9. pick org and reponame
9.a click on resources add the postgres addon
9.b open config.vars and copy the contents of the "process.env.DATABASE_URL;" into the connectionString
10. click deploy a branch
11. view your app


create a catch block.




### Deploy the Frontend

*Front end is going to live a github.io

1. go to settings and gitHub pages)
2. create a var :   __API_URL__ = 'https://herokulink.com';
3. add to the endpoints
i.e. $.post(`${__API_URL__}/db/person`, data)
4. add a catch block
* sometimes you need to flush the cache out.
* orgs are listed on the lower left on your GH Profile


create an org in github & 2 repos

create a server & .gitignore 
add to heroku
use the same dependencies


*API:*
1 - create an organization on github to hold your *client* and *server* repo’s
2 - start building your server - run `npm init`, install any npm dependencies (`express`, `cors`, `pg`) and create a `server.js` file
3 - setup basic demo routes for `GET` and `POST` requests
4 - connect your application to github (`git init` and `git remote add origin git.url`)
5 - create a new application in Heroku
6 - click on the resources tab and provision a postgres database (free plan)
7 - copy the `DATABASE_URL` config var (settings tab) and add that and your database connection code to your `server.js` file
8 - click on the Deploy tab and setup automatic deployments
9 - go to the Activity tab and watch the build process

*Client:*
1 - create a simple `index.html` and associated `app.js` file in your `client` repo (don’t forget to include jQuery)
2 - click on the Settings tab, scroll down to the GH-Pages section and point your deployments to your `master` branch
2 - create a few simple `GET` and `POST` `$.ajax` requests in your `app.js` file (for testing) - *be sure* to create an `__API_URL__` that points to your API on Heroku
3 - test to ensure your application’s are talking to each other!  you’ll likely need to fix multiple issues before this works!
[4:11 PM]
:point_up:*this is a guideline, not exact steps* - be sure to test frequently and use build logs and your `console` to help you debug



#### LAB OVERVIEW ####

- just a mobile view!!
- get a build a database with get and post routes
- create a page that allows you to add data
- if you want to create a form  ;)
- image url, book title, author
- GET /api/v1/books


