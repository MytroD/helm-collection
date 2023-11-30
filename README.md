## My Helm Chart collection

[![License](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](https://opensource.org/license/gpl-3-0)
[![Support](https://img.shields.io/badge/Support-Community-yellow)]()

This is a collecition of the awesome project.
Please be advised that the Helm Chart my not fulfill all needs and is work-in-progress.

## HOMARR
[Homarr](https://github.com/louislam/uptime-kuma) [![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/homarr)](https://artifacthub.io/packages/helm/truecharts/homarr)
> A simple, yet powerful dashboard for your server.
> Simplify the management of your server with Homarr - a sleek,
> modern dashboard that puts all of your apps and services at your fingertips.
> With Homarr, you can access and control everything in one convenient location.
> Homarr seamlessly integrates with the apps you've added, providing you with valuable 
> information and giving you complete control. Installation is a breeze, and Homarr supports a wide range
> of deployment methods..


## MEALIE
[Mealie](https://github.com/louislam/uptime-kuma) [![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/homarr)](https://artifacthub.io/packages/helm/truecharts/homarr)
> Mealie - Recipe Management for The Modern Household
> Mealie is an intuitive and easy to use recipe management app. 
> It's designed to make your life easier by being the best recipes management experience on the web
> and providing you with an easy to use interface to manage your growing collection of recipes.


## OWNCLOUD
[OwnCloud](https://github.com/louislam/uptime-kuma)
>
>


## UPTIME-KUMA
[Uptime-Kuma](https://github.com/louislam/uptime-kuma) [![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/uptime-kuma)](https://artifacthub.io/packages/search?repo=uptime-kuma)
[![Release](https://github.com/dirsigler/uptime-kuma-helm/actions/workflows/release.yaml/badge.svg?branch=main)](https://github.com/dirsigler/uptime-kuma-helm/actions/workflows/release.yaml)
> Uptime Kuma is an easy-to-use self-hosted monitoring tool.


## 🚀 Deployment

[Helm](https://helm.sh) must be installed to use the charts. Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add uptime-kuma https://helm.irsigler.cloud

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages. You can then run `helm search repo uptime-kuma` to see the charts.

To install the uptime-kuma chart:

    helm upgrade my-uptime-kuma uptime-kuma/uptime-kuma --install --namespace monitoring --create-namespace

To uninstall the chart:

    helm delete my-uptime-kuma --namespace monitoring

## ⚙️ Configuration

To get an overview of the configurable and default Values check out the Chart specific [README](./charts/uptime-kuma/README.md).

## 📝 License

[GNU General Public License version 3](./LICENSE)
