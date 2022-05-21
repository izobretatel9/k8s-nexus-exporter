# k8s-nexus-exporter classic

Basic prometheus metrics exporter for Sonatype Nexus > v3.6

The default user is admin, but to collect these metrics only the nx-metrics-all and nx-atlas-all privileges are required.
# usage in k8s
```
helm install nexus-exporter ./ -n nexus
```
## Original source
```
https://github.com/ocadotechnology/nexus-exporter
```