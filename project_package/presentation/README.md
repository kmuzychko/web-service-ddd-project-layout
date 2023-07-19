# `/presentation`

---

Contains an interface through which clients interact with the application's API. It handles incoming requests, validates inputs, and returns appropriate client responses.

In general, applications have only one interface of communication. But sometimes, it implements a few types simultaneously, and this structure should be suitable in this case:

* `/rest` - Contains RESP APIs routers, DTOs, etc.
* `/graphql` - Contains GraphQL related topics.
* `/grpc` - Contains Proto files, generated code.