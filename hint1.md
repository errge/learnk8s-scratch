There are multiple ways to handle debugging scratch containers in Kubernetes.

Recent versions made this really simple by using so called [ephemeral containers](https://kubernetes.io/docs/tasks/debug/debug-application/debug-running-pod/#ephemeral-container).

Read the documentation and start a `nilcons/debian` container as an additional debug container to get shell access.
