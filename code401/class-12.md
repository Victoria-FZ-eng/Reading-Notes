# Spring RESTful Routing & Static Files

## Spring Request Mapping, Methods:

1. Default Method / by path
2. HTTP Method
3. HTTP Headers (headers attribute, produces and consumes attributes)
4. Path Variables (single, multiple, with regex)
5. Request Parameters
6. Corner Cases (Multiple Paths Same Controller, Multiple Requests Same Controller)
7. New Request Mapping Shortcuts
8. Spring Configuration (@Controller)

## Accessing Data with JPA

check this [URL](class-11.md)

## CrudRepository, JpaRepository, and PagingAndSortingRepository in Spring Data

* CrudRepository provides CRUD functions
* PagingAndSortingRepository provides methods to do pagination and sort records
* JpaRepository provides JPA related methods such as flushing the persistence context and delete records in a batch

**Typical CRUD functionality:**

1. save(…) – save an Iterable of entities. Here, we can pass multiple objects to save them in a batch
2. findOne(…) – get a single entity based on passed primary key value
3. findAll() – get an Iterable of all available entities in database
4. count() – return the count of total entities in a table
5. delete(…) – delete an entity based on the passed object
6. exists(…) – verify if an entity exists based on the passed primary key value

References:

* [Baeldung: Spring Request Mapping](https://www.baeldung.com/spring-requestmapping).

* [Spring guide: Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/).

* [Baeldung: Comparing repositories](https://www.baeldung.com/spring-data-repositories).