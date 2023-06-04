## What are firewalls for?

Firewalls are meant to prevent unauthorized access to a network. It is essentially a security system that filters out dangerous traffic from your website.

## Why is traffic server over HTTPS?

HTTPS follows the same protocol as HTTP, but it encrypts normal HTTP requests via SSL, for an extra measure of security!

## What is monitoring used for?

Monitoring is useful for keeping track of server activity, to make sure everything is in order and nothing is broken.

## How does the monitoring tool collect data?

Monitoring data is obtained from server log files, which are generated automatically. These provide helpful information about any potential issues, about user activity and about security events.

## Why does terminating SSL at the load balancer level pose an issue?

Because it leaves the traffic between the load balancer and the server unencrypted, essentially jeopardizing the entire purpose of SSL encryption.
