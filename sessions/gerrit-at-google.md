# Gerrit at Google: Multi-master, Mutli-tenant

This talk is about hosting Gerrit at Google, gives insights into our
architecture and provides some metrics on scale. In addition, it presents
findings from the recent switch of our load-balancing infrastructure and
highlights pitfalls we encoutered.

## Gerrit at Google

* Multi-master/-tenant setup
* Replication
* Housing large projects like Android and Chromium
* Some metrics on scale
* Outages and root-causes

## Load-balancing Git/Gerrit Traffic at Google

* Sharding of hosts, projects and repositories across hundreds of serving tasks
* Optimizing different caches
* Load-balancing decisions and their impact on latency
* What garbage collection means for load-balancing and vice-versa

## Slides

The slides for this talk can be found [here](https://docs.google.com/presentation/d/1pZkXbrhcUZxO-1TEUJgBvOiJJiYWwtHOw8fegsjvCnc).

## Transcript and Recording

The recording and transcript of this talk can be found [here](https://gitenterprise.me/2017/10/10/gerrit-user-summit-gerrit-at-google/)

*[Patrick Hiesel, Google](../speakers.md#hiesel)*
