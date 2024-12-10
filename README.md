# Data Catalog Service Helm Chart

## Current version: 1.0.0 (December 10th, 2024).

## Installation

### Using the Helm repository hosted in GitHub Pages

First, add the Helm repository:

```bash
$ helm repo add data-catalog-service-helm https://candil-data-fabric.github.io/data-catalog-service-helm/
```

Then, install the Helm Chart:

```bash
$ helm install data-catalog-service data-catalog-service-helm/data-catalog-service
```

The chart will be installed using the default values. Use the provided [`values.yaml`](values.yaml) file in this repository as template to upgrade the installation with your desired parameters:

```bash
$ helm upgrade data-catalog-service -f myvalues.yaml
```

To uninstall the Helm Chart, run the following command:

```bash
$ helm uninstall data-catalog-service
```

### Cloning this repository

First, clone the repository:

```bash
$ git clone https://github.com/candil-data-fabric/data-catalog-service-helm.git
```

Once cloned, edit the [`values.yaml`](values.yaml) file to match your deployment needs and run the following command:

```bash
$ helm install data-catalog-service .
```

To uninstall the Helm Chart, run the following command:

```bash
$ helm uninstall data-catalog-service
```