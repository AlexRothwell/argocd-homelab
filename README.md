# My Argo CD cluster config

This repo contains the majority of the config for my Argo CD cluster. Currently this uses the app-of-apps pattern to include:
* A [Tailscale K8s operator](https://tailscale.com/kb/1236/kubernetes-operator) for load balancing and easy access sharing
* A sample ASP.NET Core server to prove it works
* A [dedicated Satisfactory server](https://github.com/wolveix/satisfactory-server)
* A [Skyrim together reborn server](https://wiki.tiltedphoques.com/tilted-online/guides/getting-started)
* A [Wake on LAN service](https://github.com/seriousm4x/UpSnap) (to be fixed to use a stateful set)
