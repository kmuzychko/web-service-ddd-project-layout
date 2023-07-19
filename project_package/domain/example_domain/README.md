# `/example_domain`

---

The recommended way to structure Domain packages are:

* `domain` - Contains Domain components (Entities, Value Objects, Aggregates)
* `repository` - Interface on Persistent layer of application or client to some third party which can be treated as a data source
* `service` - Domain service which holds the main business Domain logic and rules