# SuperAgent 

is a light-weight progressive ajax API crafted for flexibility, readability, 
and a low learning curve after being frustrated with many of the existing request APIs. It also works with Node.js

* GET requests
The .query() method accepts objects, which when used with the GET method will form a query-string. The following will produce the path /search?query=Manny&range=1..5&order=desc.

* HEAD requests
can also use the .query() method for HEAD requests. The following will produce the path /users?email=joe@smith.com.

* Response status
The response status flags help determine if the request was a success, among other useful information, making SuperAgent ideal for interacting with RESTful web services. 

* CORS
For security reasons, browsers will block cross-origin requests unless the server opts-in using CORS headers. Browsers will also make extra OPTIONS requests to check what HTTP headers and methods are allowed by the serve

* Promise and Generator support
SuperAgent's request is a "tunable" object that's compatible with JavaScript promises and the async/await syntax.
If you're using promises, do not call .end() or .pipe(). Any use of .then() or await disables all other ways of using the request.


# explained REST 

The whole world wide web is built on an architectural style called “REST”. REST provides a definition of a “resource”, which is what those things point to.

 the concept that people are calling “Web Services” or "APIs". It means a lot of different things to a lot of different people but the basic concept is that machines could use the web just like people do.

 computers can use those same protocols to send messages back and forth to each other. We've been doing that for a long time but none of the techniques we use today work well when you need to be able to talk to all of the machines in the entire world.