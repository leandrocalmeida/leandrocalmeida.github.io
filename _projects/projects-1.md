---
title: "Design and implementation of an In-Network Load-aware Fast Rerouting mechanism"
excerpt: "Failures in communication networks affect the quality of the services running on the end-hosts. Although some applications may tolerate a certain delay to resolve the failure, others are highly latency-dependent and need fast solutions for traffic rerouting. Fast Rerouting (FRR) is a mechanism used to quickly reroute traffic upon failures completely in the dataplane. Although there are several works related to FRR, there is no current solution that considers the status of the network to define the backup paths. In this work, we benefit from the In-network computing and programmability to design and implement a mechanism entirely in the dataplane to define backup paths based on the load of the network. The mechanism should be aware of the status of the links in terms of, e.g., end-to-end latency to set the best backup paths. Upon a failure, our solution must fast reroute the traffic to such paths without the control plane help. We will develop the mechanism totally in the dataplane by using P4 and evaluate it using real minimalist scenarios as well as simulations."
collection: projects
---

 
