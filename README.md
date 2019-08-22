# armada-prom-op

This package allows you to deploy a prometheus-operator to your cluster.

For more information about the prometheus-operator please have a look [here](https://github.com/coreos/prometheus-operator)

## Details

This package will create a serviceaccount with clusterrolees and bindings, this associated to the deployment of the prometheus-operator.

It's recommended to deploy the package inside a namespace other than default.