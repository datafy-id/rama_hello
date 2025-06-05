# `rama` Hello!

My exploration to the 100x [Red Planet Lab's rama](https://redplanetlabs.com/).

As for now, you should able to figure out how it works by reading this [small example of Profile module](./src/rama/gallery/profile_module.clj). Let your instinct guide you how it is supposed to works.

Hint: when this module deployed to the cluster, we will have *precise* indexed data accessible in `$$username->registration` and `$$profiles` pstate. Think [pstate](https://redplanetlabs.com/docs/~/pstates.html) as a standard clojure `hash-map` with some additional powers, it is indexed, and persistently stored in partitions to *disk* (i.e. durable) and accessible with our day to day clojure functions.

Stay tuned!
