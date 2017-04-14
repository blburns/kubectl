# kubectl
Repo for building container images for upstream kubectl

To build a new image, run `./build [version]`, e.g.:
```shell
PUSH_IMAGE=true ./build v1.6.1
````
The images are hosted on [quay.io/coreos/kubectl](https://quay.io/repository/coreos/kubectl?tab=tags)
