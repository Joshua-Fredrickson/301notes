## SQL

We are writing code to create the DataBase

node.pg   --wrapper--

#### CRUD

Create Read Update Destroy

DBMS - is a Postgres, mySQL

SQL uses tables
SQL statements are made up of clauses, expressions and predicates.

DDL = Data Definition Language manages the table and index structure.
DDL statements
- CREATE
- ALTER
- DROP
- TRUNCATE

creating a table

CREATE TABLE [name value] (
    column1 [constraint value]
    column1 [constraint value]
    column1 [constraint value]
)


DATA Types
- Interger
- Float
- Char
- Varchar
- Text 
- Date 
- Time
- boolean
Primary keys and Forgein keys:  Primary keys are like "id"

CRUD

Create - use CREATE 
        builds the "table".
         

Read - use the SELECT clause


Update - use the UPDATE
            SET
            WHERE

Destroy - DELETE


#### WALK THROUGH ####
make servers (this is not linear!)
add needed module
check server working
add routes


this is application Middleware for the request and "send" process

app.use(bodyParser.json());
app.use(bodyParser.rlencoded( { extended: true}));
app.use(express.static('./public'));

!!!!!!!! watch the video to add the code from the app.js creation from the 2nd video!!!!!!!

- database code

postgres will be pointed to 


##### psl #####
- pgstart
- pgstop

commands
\l = list out db's
\c = connect to db
\q = quit

command line in postgres!!   

createdb [name] - create
dropdb [name] - delete


