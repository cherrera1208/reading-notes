Class 12: CRUD
==============

Summary:

Reading
-------

[Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

1. In your own words, describe what each group of status code represents:

    * 100’s = informational. tells the user that the info has been received
    * 200’s = success. the request was handled and accepted
    * 300’s = redirection. requests are't available at expected location.
    * 400’s = error. invalid requests that time out the server; 404.
    * 500’s = server. overwhelmed and/or unreachable servers
2. What is a status code 202?

    accepted. the request was valid.

3. What is a status code 308?

    permanent redirect. the current url no longer host/provides the requested resources

4. What code would you use if an update didn’t return data to a client?

    204

5. What code would you use if a resource used to exist but no longer does?

    410

6. What is the ‘Forbidden’ status code?

    client does not have the permissions to access the resources

Videos
------

[Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw) - First 20 minutes

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

    because it has sensitive info

2. What is middleware?

    code that runs when the server is gets a request but before it get to the route.

3. What does `app.use(express.json())` do?

    lets server use json as a body

4. What does the `/:id` mean in a route?

    is a parameter, can be accessed with req.params

5. What is the difference between `PUT` and `PATCH`?

    put is a single or small change, a patch is like an update

6. How do you make a default value in a schema?

    as a JS object

7. What does a `500` error status code mean?

    overwhelmed or unreachable server

8. What is the difference between a status `200` and a status `201`?

    200 is the basic OK status, 201 is the status for created content
