# WRRC and Java

## The HTTP Request Lifecycle

1. Local Processing: Your browser extracts the "scheme"/protocol , host (www.example.com),and optional port number, resource path, and query strings.
2. Resolve an IP: if the cache lookup fails , it need to go through some steps to reach it's target and thenmaking response.
3. Establish a TCP Connection: having a completed three-way handshake and an established connection where both the client and server have received acknowledgment of the connection from the other party.
4. Send an HTTP Request.
5. Tearing Down and Cleaning Up .

## Creating a simple HTTP request using the built-in Java class HttpUrlConnection. 

**Use** HttpUrlConnection class **-->** openConnection() method , ex:

```
URL url = new URL("http://example.com");
HttpURLConnection con = (HttpURLConnection) url.openConnection();
con.setRequestMethod("GET");
```
**-->** doOutput property to true, then write a String of the form param1=value¶m2=value to the OutputStream of the HttpUrlConnection instance, ex:

```
Map<String, String> parameters = new HashMap<>();
parameters.put("param1", "val");

con.setDoOutput(true);
DataOutputStream out = new DataOutputStream(con.getOutputStream());
out.writeBytes(ParameterStringBuilder.getParamsString(parameters));
out.flush();
out.close();
```

*ParameterStringBuilder containing a static method, getParamsString(), that transforms a Map into a String*

**-->** setRequestProperty() method **-->** getHeaderField() method **-->** setting the connect and read timeouts setConnectTimeout() and setReadTimeout() methods **-->** handle cookies by CookieManager and HttpCookie and many more (Read the cookie **->** add it to cookie store **->** add the cookies to the request) **-->**  enable or disable automatically following redirects for a specific connection setInstanceFollowRedirects() method **-->** read the response getResponseCode(), connect(), getInputStream() or getOutputStream() methods **-->** read response on failed requests HttpUrlConnection.getErrorStream() **-->** Building the Full Response.




References:

* [Review: High-level HTTP](https://dev.to/dangolant/things-i-brushed-up-on-this-week-the-http-request-lifecycle-)

* [Java HTTP Request example](https://www.baeldung.com/java-http-request)