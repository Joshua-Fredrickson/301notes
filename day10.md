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
