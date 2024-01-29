There is a docker image at `ghcr.io/learnk8s/labs-fundamentals:kubescratch`.

The image is built from the `scratch` image, similar to the last lab in "Linux containers and Kubernetes".  Therefore `kubectl exec` and `kubectl cp` commands will not work.

When the image is successfully started in Kubernetes as a container in a pod, it will listen for incoming web connections and will give the solution once visited from the browser.

Can you make this work and get the answer?

Hints:
  - [If you need ideas on how to get access to a scratch container in Kubernetes](hint1.md)
  - [If you need hints about figuring out the port number](hint2.md)
