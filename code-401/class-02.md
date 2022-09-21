Readings: Express, NPM, TDD, CI/CD
==================================

Reading
-------

[An introduction to NodeJS and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

1. Explain middleware, answer as though I were a non-technical recruiter.

    middleware is kind of like a "mod" or add-on feature for express written by other publishers to address specific concerns. An example is Auth0 for authorization.

2. Express the most popular **\_\_** **\_\_** **\_\_**_\_\__.

    JavaScript back-end framework

3. Express is “unopinionated.” What does that mean?

    the developers who wrote express left a lot of freedom for users to work with rather than include strict guidelines or rules

4. What is a module and why is modularity useful to us as developers?

    a module is a reusable, scalable, and specific section of code. It's useful because it can reduce the amount of code written which reduces labor and errors.

[What is NPM?](https://docs.npmjs.com/getting-started/what-is-npm)

1. What version of npm are you running on your machine?

    v8.19.1

2. What command would you type to install a library/package called ‘jshint’ into your node project?

    `npm i jshint`

[What is TDD?](https://www.agilealliance.org/glossary/tdd/)

1. Explain why tests are important. Please explain as though I were your non technical elder.

    tests are valuable because it catches common errors early and prevents potential app-breaking bugs. It's more work up front, but it makes a smoother workflow. like "mis-en-place" in cooking; have your ingredients ready to go _before_ you start the actual cooking.

2. What are three expected benefits of testing

    reduced defects, reduced effort, improved design quality

3. Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

    individual: forgetting to run tests and writing too many tests at once. team: partial adoption and poor maintenance

[CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)

1. What are three benefits of Continuous Integration?

    ensure's everyone's code integrates, catches bugs and reduces merge conflicts

2. What is the difference between Continuos Delivery and Continuous Deployment?

    delivery is developed to release at any time, deployment deploys new features immediately

3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background

    github is the industry standard version control suite that. It's familiar and reliable. Think of office programs you may use at work like MS Office or Google Drive. They are standard and reliable and once the office is trained on them everyone can use those tools.

Bookmark and Review
-------------------

[nodeJS docs](https://nodejs.org/en/docs/)

[npm docs](https://docs.npmjs.com)

[express docs](https://expressjs.com/en/4x/api.html)

[http status codes](https://www.restapitutorial.com/httpstatuscodes.html)

[supertest](https://github.com/visionmedia/supertest)
