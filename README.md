# poteapp-helm-charts-stage
poteapp-helm-charts-stage
## Usage

[Helm](https://helm.sh) must be installed to use these charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  `helm repo add poteapp-helm-charts-stage https://poteapp.github.io/poteapp-helm-charts-stage`

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
vdigitalpartners` to see the charts.

To install the <chart-name> chart:

    helm install my-release-name poteapp-helm-charts-stage/<chart-name>

To uninstall the chart:

    helm delete my-release-name

