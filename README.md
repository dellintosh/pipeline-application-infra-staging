# pipeline-application-infra-staging

This repo holds the Kubernetes configuration files for the pipeline application.

## Target Environment

Staging

## Usage

Changes pushed to the master branch should trigger the following actions:

* a recursive application of the configuration files located under the kubernetes directory.

See the [.drone.yml](.drone.yml) file for more details.
