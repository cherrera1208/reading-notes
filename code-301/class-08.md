Class 08: APIs
==============

Summary:

Reading
-------

[API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

1. What does REST stand for?

    representational state transfer

2. REST APIs are designed around a **\_\_****\_\_**.

    resources

3. What is an identifier of a resource? Give an example.

    a URI, a unique identifier. A customer's order is an example

4. What are the most common HTTP verbs?

    GET, POST, PUT, PATCH, DELETE

5. What should the URIs be based on?

    nouns, i.e. the resources

6. Give an example of a good URI.

    ...com/orders -> order is a noun, which is good
    ...com/create-order -> create is a verb, which is bad

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

    when an API exposes large numbers of small resources

8. What status code does a successful `GET` request return?

    status code 200(ok)

9. What status code does an unsuccessful `GET` request return?

    status code 404(not found) or 201(no content)

10. What status code does a successful `POST` request return?

    code 201(created)

11. What status code does a successful `DELETE` request return?

    code 202(accepted)

Bookmark and Review
-------------------

* [RegExr](https://regexr.com/) - Pay particular attention to the cheatsheet
* [Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
* [Regex 101](https://regex101.com/)
