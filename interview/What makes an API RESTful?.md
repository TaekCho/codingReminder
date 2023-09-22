# What makes an API RESTful?

1. It uses standard HTTP methods: Get, Post, Put, Patch, Delete

2. It should have a standard data format. e.g, JSON or XML.

3. Clients and servers are completely separate. They are not on the same system, or file. They communicate with each other through request and respond.

4. Statelessness: each request from the client to the server should contain all the information needed to understand and process requests. So the server shouldn't be storing any client side states, nor data.
     In other words, each single request can be complete, and so is each single respond, without needing to know what happened before.

5. Resource-based ( Universal Resource Identifier / Locator )
