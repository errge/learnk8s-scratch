The other trick in this lab, is that the application doesn't tell you the port number it's listening on.

This is not really related to Kubernetes, more like a Linux sysadmin thing, but very useful to know: you can list all port numbers that are being used for listening with the command `netstat -nlptu`.

Use this command in your debug container to find the port number, and then you are good to go with `kubectl port-forward`.
