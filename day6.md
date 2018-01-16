# Day 6 - AJAX, JSON, HTTP AND WRRC

## JSON Reveiw
-CodeFellows has chosen to JSON with compared to xml.
JavaScript Object Notation (this is a stringified object)  -  this is a DATA Model
Serialization = is "dehydration for data structures".  this is how we interchange between client and server.

AJAX allows you to grab the data asynchronously.  (there are different methods to handle the JSON with jQuery and AJAX).
infinante sroll pagination.

call backs - i.e. "add event listeners"

JSON BASIC RULES:
- always use "
- Keys are quoted strings
- Values can be:
  - String
  - Number
  - Object
  - Array
  - true/false
  - 

JSON data via API

#### AJAX 

is Asynchronous - no specified order
SPA = single-Page Apps framework:   http://fontflame.com/

steps w/ jQuery

1. send a request
2. Register an async callback function to handle the response.
3. profit


send a request:

1. specify the request "method", URL, settings
    Methods
        - get
        - post
        - head (is a "get" request except for the data)
    jQuery has helper methods to simplify:
    $.ajax, $.load, $.get, $.getJSON, $.post

## WRRC (web request / response cycle)
            req             res


follows client/server architecture.
-see the video-

client requests to a server
    every request requires the following
    1. url
    2. Method (REST method)
    3. Headers (the meta data under the hood. i.e. etags, )

server querys a database.

the database sends the request back to the server.

the server sends the request back to the client (typically a JSON response)
    every response contains the following
    1. status code
    2. Headers
    3. Body (data, JSON)

## INTRO to HTTP



## AJAX w/ jQuery
when you see brackets in documentation.  [] are for optional parameters.

here is a AJAX call

$.ajax({
    url: 'https://pokeapi.co/api/v2/pokemon/2',
    method: 'GET',      <------ USE CAPITALS ON THE METHOD
    success: function(data, message){
        console.log('data that I got back from the api: ', data);
        $('#broadcast img').attr('src', data.sprites.front_default);  <-----this property was in the property of the the json
    }
});




## Assignment Prep


* Tips:  when creating pseudo code add "TODO"
* check out dev.twitter.com
* check out bcrypt to handle passwords
* promises remove a layer of callbacks

DNS Domain Name Server  
live server creates the server at our computer.  178.789.3.1 (ip address): 8080 (port or output source for other computers to load)