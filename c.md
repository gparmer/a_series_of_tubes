# Connecting (C) the Tubes

[Routing](https://en.wikipedia.org/wiki/Routing) uses a sequence of specialized computers to take tube data in, and "route" it in the correct direction using [routing tables](https://en.wikipedia.org/wiki/Routing_table).
This means that we need an *algorithm* for figuring out what the routing tables should be!
The main goal is to make routing tables so that the path that the inter-connected tubes take between any point *A* and *B* is the shortest.

Assuming we know how long it takes to get from each client and server to each router, and from each router to each other router, can you define an algorithm that each router could use to decide which route to take for client/server communication?
Each router needs to separately simply decide on which "output tube" send data destined for a client/server.

- **Question C1:** Can you outline such an algorithm that would let each router construct a routing table?

The [next stop](./e.md) on our tour of the tubes.
