# Spring Authentication

## Authentication
The main strategy interface for authentication is AuthenticationManager, which has only one method:

```
public interface AuthenticationManager {

  Authentication authenticate(Authentication authentication)
    throws AuthenticationException;
}
```

The most commonly used helper is the AuthenticationManagerBuilder, which is great for setting up in-memory, JDBC, or LDAP user details or for adding a custom UserDetailsService.

Once authentication is successful, we can move on to authorization, and the core strategy here is AccessDecisionManager. There are three implementations provided by the framework and all three delegate to a chain of AccessDecisionVoter instances, a bit like the ProviderManager delegates to AuthenticationProviders.

Steps: 

1. set up a user model and repo
2. create a controller for that model
3. UserDetailsServiceImpl implements UserDetailsService
gets a User from the database by username (make sure your repository has the method to make this easy!)
4. ApplicationUser implements UserDetails
use IntelliJ to implement the methods; make the boolean ones all return true
5. WebSecurityConfig extends WebSecurityConfigurerAdapter
6. registration page
7. login page

References:

* (CheatSheet)[https://github.com/codefellows/seattle-java-401d2/blob/master/SpringAuthCheatSheet.md.]
* (Overview)[https://spring.io/guides/topicals/spring-security-architecture/]