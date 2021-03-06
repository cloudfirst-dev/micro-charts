## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add micro-charts https://github.com/cloudfirst-dev/micro-charts/blob/gh-pages

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
micro-charts` to see the charts.

To install the service chart:

    helm install my-service micro-charts/service

To uninstall the chart:

    helm delete my-service
