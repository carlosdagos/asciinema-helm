# Helm Chart for asciinema

* Install asciinema

## TL;DR;

```console
$ git clone https://github.com/carlosdagos/asciinema-helm
$ cd asciinema-helm
$ helm install .
```
## Installing the Chart

To install the chart with the release name `my-asciinema`:

```console
$ helm install --name my-asciinema .
```

## Uninstalling the Chart

To uninstall/delete the my-release deployment:

```console
$ helm delete my-asciinema
```

The command removes all the Kubernetes components associated with the chart
and deletes the release.

## Configuration

See the [values.yaml](values.yaml) file for all the configuration options.

## TODO

This still needs _a lot_ of polishing.
