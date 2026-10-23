---
title: "Splitting and Parallelizing Proofs"
url: "https://blog.ezkl.xyz/post/splitting/"
date: "2023-10-27"
feed_url: "https://blog.ezkl.xyz/index.xml"
---
In our last post we discussed how to leverage unblinded Advice columns to commit to data in a low overhead manner. In this post we’ll discuss how to leverage these commitments to split a proof into multiple parts. A natural limitation of most proving systems is that they require all the data to be proven over to be available at the same time.
