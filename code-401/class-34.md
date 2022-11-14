Reading: API Integration
========================

Reading
-------

* [Review API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)

1. Explain the different between a query string parameter and a path parameter.
    * path parameter defines the resource location, while the query parameter defines sort, pagination, or filter operations.
2. What would our API URL with a path id parameter be given the following information:
    1. Domain: `http://our-site.com`
    2. `v3`
    3. model name: `stuff`
    4. id: `things`
3. We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.
    * an interface is part of a common and standardized API

* [Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

1. Describe how you would use middleware to implement basic and bearer auth.
    * middleware sits between the req and res. The auth middleware will check credentials as it passes
2. Describe the handshake necessary to implement OAuth.
    * a .get method to the 3rd party OAuth system
3. Describe how Role Based Access Control works to a non-technical friend.
    * different users require different levels of access depending on their role. It's the same as key access to specific rooms in a secured building. The person is given the access they need to get the job done
