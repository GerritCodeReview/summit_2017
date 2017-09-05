# Load-balancing Git/Gerrit Traffic at Google

We recently reworked the load-balancing infrastructure for serving Git/Gerrit
traffic at Google. This talk is about the design of this infrastructure and some
of the pitfalls we encountered along the way, including:

* Sharding of hosts, projects and repositories across hundreds of serving tasks
* Optimizing different caches
* Load-balancing decisions and their impact on latency
* What garbage collection means for load-balancing and vice-versa


*[Patrick Hiesel, Google](../speakers.md#hiesel)*
