# tsync-charts

* Unique services need to be created for each node, or use localhost, and don't use service (already has hostNetwork).
* Helm does not allow for receiving all nodes with label, then creating objects accordingly, so again, the values file need to be paramatized.
* Each tsync configuration change requires a daemonset restart, include gps parameters, if the services are only localhost, otherwise the grpc service could be used to configure on-the-fly.
