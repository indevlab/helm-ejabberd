
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/ejabberd)](https://artifacthub.io/packages/search?repo=ejabberd)

# Helm chart for ejabberd

This repository holds a helm chart for [ejabberd](https://github.com/processone/ejabberd)
which
> [...] is an open-source, robust, scalable and extensible realtime platform
> built using Erlang/OTP, that includes XMPP Server, MQTT Broker and SIP Service.

The chart configures the environment needed to build and run ejabberd kubernetes
clusters. Additionally, the `values.yaml` file allows to include most of the
configuration items, ejabberd offers in their [`ejabberd.yml`](https://github.com/processone/ejabberd/blob/master/ejabberd.yml.example).

## Current state

The chart is under development, meaning there is room for enhancements and
improvements. The [issue tracker](https://github.com/indevlab/helm-ejabberd/issues)
may be used to define roadmap items.

The chart is functional and needs testing. Please report back if anything does
not work as expected.

Contributors and PRs are also welcome.
