## hyport

Kubernetes-native hosting for game servers. A server that starts, is reachable, and after a
node failure comes back in under a minute on the same IP and port — losing at most seconds of data.

A successor in spirit to Pterodactyl, but not a fork and not a copy: own code, own model.

### What sets it apart

- **Failover across nodes** — the allocation (IP:port) stays, players reconnect to the same address.
- **Continuous encrypted ZFS replication** to a cold peer copy on another node.
- **Self-healing by default** — every multi-step flow gets a deadline, stuck detection and safe auto-repair, or reports clearly.
- **A technical control plane** — no billing, no shop; sales portals talk to the API.

### Status

In active development, no public release yet.
