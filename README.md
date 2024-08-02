# Cozystack Infra

This repo contains scripts used to start up the baseline infrastructure for [Cozystack]

The instructions for matchbox, dnsmasq are based on [PXE Installation] from Cozystack docs

In addition to those, we have also configured Docker Registry proxies, or [Pull Through Image Cache] according to Talos Linux

And finally, a [pi-hole] for DNS (and [pi-hole exporter]) according to the Docker Compose instructions

[Cozystack]: https://github.com/aenix-io/cozystack
[PXE Installation]: https://cozystack.io/docs/talos/installation/pxe/#netboot-server
[Pull Through Image Cache]: https://www.talos.dev/v1.7/talos-guides/configuration/pull-through-cache/
[pi-hole]: https://github.com/pi-hole/docker-pi-hole
[pi-hole exporter]: https://github.com/eko/pihole-exporter
