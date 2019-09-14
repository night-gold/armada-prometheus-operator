# armada-prom-op

This package allows you to deploy a prometheus-operator to your cluster using default configuration from their github.

For more information about the prometheus-operator please have a look [here](https://github.com/coreos/prometheus-operator)

## Versions

Package: v1.0.0
App: [prometheus operator 0.33.0](https://github.com/night-gold/armada-prom-op)

## Details

This package will create a serviceaccount with clusterrolees and bindings, associated to the deployment of the prometheus-operator.

It's recommended to deploy the package inside a namespace other than default.

## Prerequisites

If there is any prerequisites for deployment, like kubernetes version or databases or other.