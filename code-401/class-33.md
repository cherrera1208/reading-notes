Reading: `<Login />` and `<Auth />`
===================================

Reading
-------

[What is Role Based Access Control (RBAC)?](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)

1. What is Role Based Access Control (RBAC)?
    * restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control
2. Share some an example of RBAC including all possible CRUD operations and correlating roles.
    * admin, all CRUD operations. manager, create, read, update. Employee, read and create. User, read
3. What are the Benefits of RBAC?
    * relieve the workload of IT by giving appropriate personnel the ability to CRUD their data

Compare and Contrast the following two Libraries and the following questions. Yes, they are similarly named.

[react-cookie library](https://www.npmjs.com/package/react-cookie)

[react-cookies component](https://www.npmjs.com/package/react-cookies)

1. Describe some `react-cookie` features.
    * Javascript object with all your cookies. The key is the cookie name.
2. Describe some `react-cookies` features.
    * To be able to access user cookies while doing server-rendering, you can use plugToRequest or setRawCookie.
3. Which library would you prefer would you prefer? Why?
    * cookies looks like it's less hands on, but may limit control. I'd choose the right one for the job
