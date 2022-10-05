# Build Instructions

The base tag this release is branched from is `v3.9.0-rancher1` on the upstream repo https://github.com/rancher/helm.git

There is no automated CI build for this repository. During the Docker build of the Rancher Shell image, this repo is cloned and "make" is called to build the Rancher custom Helm executable. That executable is part of the Rancher Shell Docker image.

###Build Helm

```
make
```

The Rancher Helm executable is built into the ./bin/ directory.
