# 🔐 Manage Network Security

## Objective

Configure network-level access for web services and validate accessibility from a remote machine.

## Task Steps

1. From the **controller** machine, test access to the default web server on `serverb`:

http://serverb.example.com


2. On the `serverb` machine, configure the **firewalld** service to allow the `httpd` service to listen on **port 82/TCP**.

3. From the **controller** machine, test access again — this time using the custom port:

http://serverb.example.com:82


> ✅ Ensure that all firewall changes are **permanent** and survive reboots.
