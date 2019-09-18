# Self destruct a Kubernetes Pod

For various reasons, such as trigger rescheduling, you may want to self destruct the Kubernetes Pod from a container running in it.


## Project components
- Go executable
- Dockerfile
    - Build executable
    - Build helm chart
    - Test with [kind](https://github.com/kubernetes-sigs/kind)
    - Copy 


## Tests
Go code is compiled as part of a build step in a multi-stage Dockerfile