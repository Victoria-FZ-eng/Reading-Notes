# APIs

**REST** (Representational State Transfer).

REST APIs are designed around a **resources**.

**Identifier** of resource, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be: `https://weather-data.com/10-days`

The most common HTTP verbs are *GET, POST, PUT, PATCH, and DELETE*.

URIs be based on nouns (the resource) and not verbs (the operations on the resource).
```
https://adventure-works.com/orders // Good

https://adventure-works.com/create-order // Avoid
```

**‘chatty’ web API?**  APIs that expose a large number of small resources. It's bad we avoid doing this.

What status code does a successful GET request return? *HTTP status code 200 (OK)* other than that its error.

What status code does a successful POST request return? *HTTP status code 201 (Created).*

What status code does a successful DELETE request return? *HTTP status code 204*.

#### RegEx

check the links Below ^_^ .



References : 

* [API's](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design).
* [RegExr](https://regexr.com/).
* [Tutorial/regex](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285).
* [regex 101](https://regex101.com/).

