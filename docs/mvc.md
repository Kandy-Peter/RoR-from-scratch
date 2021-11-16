# the Model View Controller(MVC) Pattern
 GET /about HTTP/1.1
 Host: 127.0.0.1

##Routers
 Matches for the URL that is the requested

 GET for "/about"

 Isee you requested "/about", we'll give that to the AboutController to handle

##Model
Database wrapper 

User
* Query for record
* wrap individual record


#Views
Your request body content
*HTML
*CSV
*PDF
*XML

This is waht gets sent back to the browser and displayed

## Controllers
Decide how to process and define a response
it's a like the brain