# Alpine Linux with OpenShift CLI

A Docker image built from Alpine Linux. Installs GNU C Library and the OpenShift CLI.

## Arguments

Argument      | Default | Description
--------------|---------|-------------
OC_VERSION    | 3.11.0  | Version of the OpenShift CLI, see [RedHat documentation](https://docs.openshift.com/container-platform/3.11/cli_reference/get_started_cli.html)
GLIBC_VERSION | 2.31-r0 | Version of GNU C Library, see [project repository](https://github.com/sgerrand/alpine-pkg-glibc)
