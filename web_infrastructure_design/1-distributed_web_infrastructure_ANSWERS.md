## Which load balancer distribution algorithm is being configured here?

This website is using an active-active load balancer setup. What this means, is that the load balancer will distribute the server workload across all available servers, in order to - ideally - prevent any one server of getting overloaded.

## And what is the other option?

The other option would've been an active-passive setup, in which case - rather than every server being active at all times - any servers outside of the first (the primary server) would be on standby until they are needed (as in, until the first server gets overwhelmed/becomes unavailable)

## Is there a SPOF in this framework?

Yes. However, in this case, the SPOF wouldn't be the servers, but rather the load balancer itself.

## Are there any security issues with this framework?

Yes. For one, there are no firewalls protecting any of the servers, and it'd be ideal to utilize HTTPS instead of HTTP at this point. Also, there is no monitoring in any of the servers.
