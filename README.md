# OpenShift Build

OpenShift Build usage based off of Shipwright.

## Setup

1. OpenShift 4.18+
2. OpenShift Build Operator installed

## Usage

### Create Build

Make sure to update git url and output image in `build.yaml`.  Then apply:

```shell
oc apply -f ./build.yaml
```

### Run Build

Everytime you need to run a build:

```shell
oc apply  -f ./build-run.yaml
```

## References

1. [OpenShift Build Docs](https://docs.redhat.com/en/documentation/builds_for_red_hat_openshift/1.3/html/work_with_builds/index)
2. [Shipwright Docs](https://shipwright.io/docs/build/buildrun/)
