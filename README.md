
Basic API application using Spring Boot
=======================================

by James Valles
--------------

**GET** posts/

Returns all posts

**GET** posts/id 

Returns specific post

**POST** posts/ 

Adds a new post

**DELETE** posts/id 

Removes specific post

**PUT** posts/id 

Updates post

>SAMPLE JSON

{
"zipcode": 1,
"city": "Sample Title",
"state": "Body text goes here"
}

Homepage uses Bootstrap cover template by @mdo
Runs on MYSQL Database as set in application.properties