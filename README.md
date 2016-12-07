*A simple load balancer written in elixir.*

# TODO
1. Support round-robin load balancing.
2. Assign weights to each node.
3. Make system fault-tolerant. If a node suddenly goes down. The load balanace
should be able to redirect the user to a different node
