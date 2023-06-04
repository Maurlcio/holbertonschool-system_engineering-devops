## Why are the load balancers arranged as a cluster?

This is to ensure that the load balancer(s) doesn't become a SPOF liability. This way, if one load balancer experiences issues, the other can take over without jeopardizing the entire infrastructure.
