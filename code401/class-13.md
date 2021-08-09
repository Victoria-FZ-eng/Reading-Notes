# Related Resources and Integration Testing


1. One-to-One Relationship 

   @OneToOne annotation and @RestResource annotation (optional)to customize the endpoint

   extends Repository

   **Testing** => saving Library and Address objects by making POST requests to the collection resources.Then it saves the relationship with a PUT request to the association resource and verifies that it has been established with a GET request to the same resource.

2. One-to-Many Relationship

   @OneToMany and @ManyToOne annotations and the optional @RestResource annotation .

   **Testing** => saving a Library instance and two Book instances, sends a PUT request to each Book object's /library association resource, and verifies that the relationship has been saved

3. Many-to-Many Relationship

   @ManyToMany annotation, and optional @RestResource.


## Testing

@ExtendWith - @ContextConfiguration - @WebAppConfiguration - WebApplicationContext Object - @Beans - 

References:

* [Related data in Spring (focus on the relationship annotations, not the curl requests)](https://www.baeldung.com/spring-data-rest-relationships).

* [Baeldung: Spring Integration Testing](https://www.baeldung.com/integration-testing-in-spring).