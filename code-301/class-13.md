Class 13: More CRUD
===================

Summary:

Reading
-------

[CRUD Basics](https://medium.com/geekculture/crud-operations-explained-2a44096e9c88)

1. Which HTTP method would you use to update a record through an API?

    PUT

2. Which REST methods require an ID parameter?

    UPDATE & DELETE

Videos
------

[Speed Coding: Building a CRUD API](https://www.youtube.com/watch?v=EzNcBhSv1Wo) (_Watch a Twitch streamer code an Express API in 20 minutes!_)

1. What’s the relationship between REST and CRUD?

    They have similar verbiage with similar properties, but CRUD handles data in databases and REST handles the resources passing through URLs. They often need to coordinate, or "handshake" to display the data.

2. If you had to describe the process of creating a RESTful API in 5 steps, what would they be?

    1.install the framework and packages (express)

    2.make PORT and API in .env, listen function

    3.establish routes (starting with home '/' and star '\*\')

    4.use the 'required' components (app.use...)

    5.connect developed all modules
